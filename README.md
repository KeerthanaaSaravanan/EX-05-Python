# EX-05: Find the square root of a number

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
Program to find the square root for the given number(newton's method) using function.
Developed by: Keerthana Saravanan
RegisterNumber:  23013398
def newton_sqrt(num: float, tolerance: float) -> float:
    x = num
    while True:
        root = 0.5 * (x + (num / x))
        if abs(root - x) < tolerance:
            break
        x = root
    return root
num = int(input())
tolerance = 1e-10
result = newton_sqrt(num, tolerance)
print(f"Square root of the number: {result}")


```

## Output:
![Screenshot 2023-11-26 162817](https://github.com/KeerthanaaSaravanan/EX-05-Python/assets/145742596/6f61ab58-e92c-4f63-9c5d-95e244e3e63e)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
