# task1
simple calculator


## task 1 :simple calculator

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b != 0:
        return a / b
    else:
        return "Error found: Division by zero"


num1 = int(input("Enter the 1st number: "))
num2 = int(input("Enter the 2nd number: "))
op= input("Enter operation (+, -, *, /): ")


if op == "+":
    result = add(num1, num2)
elif op == "-":
    result = subtract(num1, num2)
elif op == "*":
    result = multiply(num1, num2)
elif op == "/":
    result = divide(num1, num2)
else:
    result = "Incorrect operation"


print("Result is: ",result)

