🧮 Simple Arithmetic Calculator (Python)

A beginner-friendly Python Simple Calculator that performs basic arithmetic operations such as Addition, Subtraction, Multiplication, and Division.
This project is great for learning Python input handling, conditional statements, and mathematical operations.

🚀 Features

➕ Addition

➖ Subtraction

✖️ Multiplication

➗ Division

User-friendly console-based interface

Handles invalid menu choices

🛠️ Technologies Used

Python 3

📌 How It Works

The user enters two numbers.

A menu is displayed with four operations.

The user selects a choice (1–4).

The calculator performs the selected operation and prints the result.

If the user enters an invalid choice, an error message is shown.

📂 Code
# python-project-
print("Simple Calculator")

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = int(input("Choose option (1-4): "))

if choice == 1:
    print("Result:", a + b)
elif choice == 2:
    print("Result:", a - b)
elif choice == 3:
    print("Result:", a * b)
elif choice == 4:
    print("Result:", a / b)
else:
    print("Invalid choice")
