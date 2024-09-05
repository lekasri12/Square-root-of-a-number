# Find the square root of a number
## DATE:

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
Developed by: G Leka Sri
RegisterNumber: 212223100025
def newtons_method_sqrt(number, tolerance=1e-10):
    if number < 0:
        return None 
    
    guess = number / 2.0
    while True:
        new_guess = 0.5 * (guess + number / guess)
        if abs(new_guess - guess) < tolerance:
            return new_guess
        guess = new_guess
number = float(input())
sqrt_value = newtons_method_sqrt(number)

if sqrt_value is not None:
    print(f"Square root of the number: {sqrt_value}")
else:
    print("Square root is not defined for negative numbers.")  
*/
```

## Output:
![Screenshot 2024-09-05 134417](https://github.com/user-attachments/assets/0cd87623-d3bf-4f4d-bebf-8be28384e6bc)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
