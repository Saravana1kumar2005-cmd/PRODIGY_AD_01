
TASK 1 : Simple Calculator – Python CLI Tool

Overview:
This is a basic command-line calculator written in Python. It allows users to perform five fundamental arithmetic operations:
- Addition (+)
- Subtraction (−)
- Multiplication (×)
- Division (÷)
- Percentage (%)

How It Works:
1. Displays a menu of operations.
2. Prompts the user to select an operation (1–5) and input two numbers.
3. Performs the selected arithmetic operation.
4. Prints the result to the console.

Features:
- Input validation for operation choice
- Handles division by zero gracefully
- Computes percentage as: (num1 / 100) * num2

How to Run:
Make sure Python is installed, then run the script using:
    python calculator.py

Example Usage:
Simple Calculator
Select operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (×)
4. Division (÷)
5. Percentage (%)
Enter choice (1/2/3/4/5): 1
Enter first number: 10
Enter second number: 5
10.0 + 5.0 = 15.0

Notes:
- Inputs are cast to float for decimal support.
- Invalid choices are handled with an error message.
- Division by zero is explicitly checked to avoid runtime errors.
"""
