# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
~~~
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

f = lambda a, b : a + b

print(f(num1, num2))
~~~

## Output
Enter first number: 5
Enter second number: 7
12

## Result
The program demonstrates the use of a lambda function, which is an anonymous, one-line function in Python. By defining f = lambda a, b : a + b, we create a function that takes two arguments and returns their sum immediately, which is then called using the inputs provided by the user.
