# codtech-task1
NAME:GUNASHEKHAR

COMPANY:CODTECH IT SOLUTIONS
DOMAIN:PYTHON
DURATION:AUGUST TO SEPTEMBER
MENTOR:MUZAMMIL AHMED

# Overview of the Basic Calculator Program
Purpose:
The program is designed to perform basic arithmetic operations, including addition, subtraction, multiplication, and division. It interacts with the user via the command line to perform these operations on two numbers provided by the user.

Key Features:
User Interaction:

Prompts the user to choose an arithmetic operation.
Requests two numerical inputs from the user.
Displays the result of the chosen operation.
Operations Supported:

Addition: Computes the sum of two numbers.
Subtraction: Computes the difference between two numbers.
Multiplication: Computes the product of two numbers.
Division: Computes the quotient of two numbers, handling division by zero gracefully.
Error Handling:

Division by Zero: If the user attempts to divide by zero, an error message is displayed instead of crashing the program.
Invalid Input: Handles cases where the user inputs non-numeric values by catching ValueError and informing the user of the invalid input.
User Experience:

Provides a menu with numbered options for selecting the desired arithmetic operation.
Prompts the user for confirmation if they want to perform another calculation after completing the current one.
Continues to operate until the user chooses to exit.
Program Flow:
Display Menu:

The program starts by displaying a menu of operations: addition, subtraction, multiplication, and division.
User Choice:

The user is prompted to select an operation by entering a corresponding number (1, 2, 3, or 4).
Input Numbers:

After selecting an operation, the user is asked to input two numbers. These inputs are converted to floating-point numbers for calculations.
Perform Operation:

Based on the user’s choice, the program performs the selected arithmetic operation using predefined functions (add, subtract, multiply, divide).
Display Result:

The result of the operation is displayed to the user. If the operation is division by zero, an error message is shown.
Repeat or Exit:

The user is asked if they wish to perform another calculation. If the answer is "yes", the program loops back to the menu. If "no", the program exits.
Functions:
add(x, y): Returns the sum of x and y.
subtract(x, y): Returns the difference between x and y.

