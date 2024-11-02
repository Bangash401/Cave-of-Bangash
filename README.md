Overview
This is a simple console-based calculator program implemented in C++. It supports a variety of mathematical operations, including basic arithmetic, exponentiation, square roots, logarithms, and trigonometric functions.

Features
1. Basic Operations: Addition, subtraction, multiplication, and division.
2. Advanced Operations: Exponentiation, square root, and logarithm (base 10).
3. Trigonometric Functions: Sine, cosine, tangent, and their inverses.
4. User-Friendly Interface: Clear menu and prompts for user input.
5. Input Validation: Checks for invalid operations such as division by zero and invalid logarithm inputs.


Prerequisites
1. A C++ compiler (e.g., g++, Visual Studio, etc.).
2. Basic knowledge of how to compile and run C++ programs.

How to Compile

1. Download or clone the repository containing the calculator.cpp file.
2.Open a terminal or command prompt.
3.Navigate to the directory where the calculator.cpp file is located.
4.Compile the program using the following command:

g++ -o calculator calculator.cpp

How to Run

1. After compiling, run the program using:
   
./calculator

Usage

1. Upon starting the program, a menu will be displayed with available operations.
2. Enter the corresponding number for the operation you wish to perform.
3. Follow the prompts to enter the required numbers.
4. The result will be displayed after each operation.
5. To exit the program, select the "Exit" option from the menu.

Example Operations

1. Addition: Enter 1, then input two numbers to see their sum.
2. Logarithm: Enter 7 and input a positive number to see its base-10 logarithm.
3. Sine Function: Enter 8, then input a number in radians to see its sine value.

Notes

1. Trigonometric functions expect input in radians.
2. Ensure that you input valid numbers to avoid runtime errors.
3. The calculator handles errors such as division by zero and invalid logarithm inputs gracefully.
