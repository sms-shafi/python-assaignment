Task 1

a=input('Enter the first number: ')
b=input('Enter the second number: ')
#These lines prompt the user to enter two numbers.
#input() always returns a string, so we need to convert them to integers.

a=int(a)
b=int(b)
#Converts the string inputs to integers so you can do math with them.

ab1=(a+b)
print('Addition: ',ab1)
#Adds the two numbers and prints the result.

ab2=(a-b)
print('Subtraction: ',ab2)
#Subtracts the second number from the first and prints the result.

ab3=(a*b)
print('Multiplication: ',ab3)
#Multiplies the two numbers and prints the result.

ab4=(a/b)
print('Dividion: ',ab4)
#Divides the two numbers and prints the result.

