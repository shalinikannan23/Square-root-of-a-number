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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by:shalini.k
RegisterNumber:  212222240095
def newton_method(number,num_iters=100):
    a=float(number)
    for i in range(num_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
*/
```
## Output:
![image](https://github.com/shalinikannan23/Square-root-of-a-number/assets/118656529/f695c1fc-a3d5-45a6-9fb0-0a8ad9f8ff53)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
