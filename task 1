#include <iostream>

using namespace std;

int main() {
    float num1, num2;
    char op;
    
    // Input first number
    cout << "Enter first number: ";
    cin >> num1;
    
    // Input second number
    cout << "Enter second number: ";
    cin >> num2;
    
    // Input operation
    cout << "Enter operation (+, -, *, /): ";
    cin >> op;
    
    // Perform operation and display result
    switch(op) {
        case '+':
            cout << "Result: " << num1 + num2 << endl;
            break;
        case '-':
            cout << "Result: " << num1 - num2 << endl;
            break;
        case '*':
            cout << "Result: " << num1 * num2 << endl;
            break;
        case '/':
            if (num2 != 0)
                cout << "Result: " << num1 / num2 << endl;
            else
                cout << "Error! Division by zero." << endl;
            break;
        default:
            cout << "Invalid operation!" << endl;
    }
    
    return 0;
}
