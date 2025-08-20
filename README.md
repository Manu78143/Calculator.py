# Calculator.py
"A simple Python calculator that performs addition, subtraction, multiplication, and division. Built as a beginner project using Pydroid 3. Easy to understand, menu-driven, and perfect for learning Python basics."

print("Simple Calculator")

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print("Choose operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter choice (1/2/3/4): ")

if choice == "1":
    print("Result:", a + b)
elif choice == "2":
    print("Result:", a - b)
elif choice == "3":
    print("Result:", a * b)
elif choice == "4":
    if b != 0:
        print("Result:", a / b)
    else:
        print("Error! Division by zero.")
else:
    print("Invalid choice")