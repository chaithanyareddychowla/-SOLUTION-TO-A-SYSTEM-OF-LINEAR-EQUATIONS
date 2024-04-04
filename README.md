# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: CHOWLA CHAITHANYA
#RegisterNumber: 2305002004
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
x=np.linalg.solve(a,b)
print(x)
```
## Output:
![image](https://github.com/chaithanyareddychowla/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/165985172/3ad76aa1-e6a7-4548-9e4e-001c0a603b14)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

