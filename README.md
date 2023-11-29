# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
#Python program to find the square root for the given number(newton's method) using function.
#Developed by:Bhuvanesh.S.R
#Register number:23013380
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))

```

## Output:
![square root python SS](https://github.com/Bhuvanesh-Suresh/Square-root-of-a-number/assets/145742661/4965db2e-6f31-4939-8ed1-538f7d2e52bf)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
