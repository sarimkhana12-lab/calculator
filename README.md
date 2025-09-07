# calculator
mini calculator which made using python that can do simple calculations like +,-,/,*,%,^
num1 = float(input("Enter your first number: "))
num2 = float(input("Enter your second number: "))

print("Choose operation: +, -, *, /, %, ^")
op = input("Enter operation: ")

if op == "+":
    print("Result =", num1 + num2)
elif op == "-":
    print("Result =", num1 - num2)
elif op == "*":
    print("Result =", num1 * num2)
elif op == "/":
    if num2 != 0:
        print("Result =", num1 / num2)
    else:
        print("Error: Cannot divide by zero")
elif op == "%":
    if num2 != 0:
        print("Result =", num1 % num2)
    else:
        print("Error: Cannot modulus by zero")
elif op == "^":
    print("Result =", num1 ** num2)   # Power
else:
    print("Invalid operation")
