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
#Program to find the solution for the given linear equations.

#Developed by: ELJAA SAM S C

#RegisterNumber:25009107

import numpy as np

A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]

B=np.array([-9,4,-1])

C=np.linalg.solve(A,B)

print(C)


print(x)
## Output:
<img width="1317" height="50" alt="image" src="https://github.com/user-attachments/assets/0985ddfa-5be0-47f0-a726-1bd7654dcecd" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

