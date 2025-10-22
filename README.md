# Assignment-1
# Task 1: Perform Basic Mathematical Operations

## Problem Statement
Write a Python program that performs basic mathematical operations on two numbers entered by the user.
## Solution
Use the following code:
s1=int(input("Enter the 1st number"))
s2=int(input("Enter the 2nd number"))
a=s1+s2
s=s1-s2
m=s1*s2
n=s1/s2
print("Addition =",a)
print("Subtraction =",s)
print("Multiplication =",m)
print("Division =",n)

#Task 2: Create a Personalized Greeting
## Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.
## Solution
Used the following code:
s1=input("Enter your first name")
s2=input("Enter your last name")
print("Hello, ",s1," ",s2,"!"," Welcome to the Python program.",sep="")

Instead of the last code we could have also used : print(f"Hello {s1} {s2}! Welcome to the Puthon program.")
