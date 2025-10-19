# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
a = int(input("Enter the first integer (a): "))
b = int(input("Enter the second integer (b): "))
f = lambda x, y: x + y
print("The sum of", a, "and", b, "is:", f(a, b))
## Output
Enter the first integer (a): 7
Enter the second integer (b): 5
The sum of 7 and 5 is: 12

## Result
The code executed successfully
