## ===========================================================
## Project Title:
#### Hypotenuse Activity
## Description: 
#### This program is a program that calculates the hypotenuse of a right triangle 'pow()" and "sqrt()' from the math library.
## Input Needed
### Enter the following values:
#### •a
#### •b
## Sample Output
#### Inputed Value:
#### a = 7
#### b = 9
#### Expected Output:
#### "The hypotenuse's length is 11.40"
## Programmer:
#### Nathalie Kate B. Subido
## Section:
####  8-Sampaguita
## ============================================================

### Importing math library
import math

print("="*50)
print("        Hypotenuse calculator!")
print("="*50)

### Input stage to get the given values
a = (float(input("Enter the length of the first shortest side (a): ")))
b = (float(input("Enter the length of the second shortest side (b): ")))

### Square a and b
a_squared = pow(a,2)
b_squared = pow(b,2)

### Add them to get c squared
c_squared = a_squared + b_squared

### Calculate the square root using sqrt.
c = math.sqrt(c_squared)

#Output stage - show the final length of the hypotenuse
print("="*50)
print(f"     The hypotenuse's length is {c:.2f} ")
print("="*50)
