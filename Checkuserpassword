//Functions revision made by me :o
//This program might be easily cracked so use it for fun 

#include <iostream>
using namespace std;

string username;
string userPassword;

void start() {
    cout << "Enter your username\n";
    cin >> username;
    cout << "Welcome " << username << "..\n";
}

bool checkpassword() {
    cout << "Please enter your password:\n";
    cin >> userPassword;
    while (userPassword != "91455") {
        cout << "Wrong password, try again..\n";
        cout << "Please enter your password: ";
        cin >> userPassword;
    } //remember there is no if statement here
    cout << "Correct password! Welcome back " << username << "\n";
    cout << "Here is your data:\n"; //u can place your data here and build it into exe 
    return true;
}

int main() {
    start();
    cout << "Before we proceed, we need your password, " << username << endl;
    checkpassword();
    return 0;
}
