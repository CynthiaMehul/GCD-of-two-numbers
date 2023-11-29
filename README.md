# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Cynthia Mehul J
RegisterNumber:  23009725
*/
a=int(input())
approx=0.5*a
for i in range(1,10):
    b=0.5*(approx+a/approx)
    approx=b
print("Square root of the number:",b)

```

## Output:
![gcd of two number](gcd.png)
![label](/Output%20GCD.jpg)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
