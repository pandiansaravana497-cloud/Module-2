# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
def result(a, b):

    if b == 0:
        print("Error: Division by zero is not allowed.")
    else:
        modulo = a % b
        print("The result of", a, "%", b, "is:", modulo)
try:
    a = int(input("Enter the first integer (a): "))
    b = int(input("Enter the second integer (b): "))
    result(a, b)
except ValueError:
    print("Invalid input. Please enter valid integers.")

## Output
Enter the first integer (a): 17
Enter the second integer (b): 5
The result of 17 % 5 is: 2

## Result
The code executed successfully
