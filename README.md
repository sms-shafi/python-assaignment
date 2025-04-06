# Task 1 – Basic Arithmetic Operations

This Python program takes two numbers as input from the user and performs basic arithmetic operations: addition, subtraction, multiplication, and division.

---

# Code

```
a = input('Enter the first number: ')
b = input('Enter the second number: ')
# These lines prompt the user to enter two numbers.
# input() always returns a string, so we need to convert them to integers.

a = int(a)
b = int(b)
# Converts the string inputs to integers so you can do math with them.

ab1 = (a + b)
print('Addition: ', ab1)
# Adds the two numbers and prints the result.

ab2 = (a - b)
print('Subtraction: ', ab2)
# Subtracts the two numbers and prints the result.

ab3 = (a * b)
print('Multiplication: ', ab3)
# Multiplies the two numbers and prints the result.

ab4 = (a / b)
print('Dividion: ',ab4)
Divides the first number by the second and prints the result.

```
# sample output

---

```
Enter the first number: 10
Enter the second number: 5
Addition:  15
Subtraction:  5
Multiplication:  50
Dividion:  2.0
```
# Task 2 - Greet the User with Full Name

This program asks for the user's first and last name, then greets them using their full name.

---

# Code

```
a = input('Enter your first name: ')
# This line asks the user to enter their first name and stores it in variable a.

b = input('Enter your last name: ')
# This line asks the user to enter their last name and stores it in variable b.

c = a + " " + b
# This joins the first name and last name with a space in between, and stores the full name in variable c.

print('Hello, ' + c + '! Welcome to Python program.')
# This prints a greeting message using the full name entered by the user.
```
# sample output
---

```
Enter your first name: Shaik
Enter your last name: shafi
Hello, Shaik shafi! Welcome to Python program.

