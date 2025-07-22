# Decision making statements in in C++(If/Else)
# Pratyush Saha
# PRN- 24070123078
if-else Statements in C++ and Their Uses
The if-else statement is used in C++ to make decisions in a program.
It allows the program to execute certain code only if a condition is true, and optionally do something else if it’s false.

Basic Syntax
cpp
Copy
Edit
if (condition) {
    // Code runs if condition is TRUE
} else {
    // Code runs if condition is FALSE
}
Types of if Statements
1. Simple if Statement
Executes code only when the condition is true.

cpp
Copy
Edit
#include <iostream>
using namespace std;

int main() {
    int age = 18;

    if (age >= 18) {
        cout << "You are eligible to vote." << endl;
    }

    return 0;
}
2. if-else Statement
Executes one block if the condition is true, and another block if false.

cpp
Copy
Edit
int age = 16;

if (age >= 18) {
    cout << "You can vote." << endl;
} else {
    cout << "You are too young to vote." << endl;
}
3. if-else if Ladder
Used when there are multiple conditions.

cpp
Copy
Edit
int marks = 85;

if (marks >= 90) {
    cout << "Grade: A" << endl;
} else if (marks >= 75) {
    cout << "Grade: B" << endl;
} else if (marks >= 50) {
    cout << "Grade: C" << endl;
} else {
    cout << "Grade: F (Fail)" << endl;
}
4. Nested if Statements
Placing one if inside another.

cpp
Copy
Edit
int age = 20;
bool hasID = true;

if (age >= 18) {
    if (hasID) {
        cout << "Entry allowed." << endl;
    } else {
        cout << "ID required for entry." << endl;
    }
} else {
    cout << "You are underage." << endl;
}
Uses of if-else Statements
Decision-making (choosing actions based on conditions).

Validation (checking input, like age or password).

Menu-driven programs (deciding which option user selected).

Game development (checking win/loss conditions).

Real-life conditions (like comparing numbers, handling errors).
