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
```python
#Program to find the eigen values and eigen vectors.
#Developed by: SANJAY M
#RegisterNumber: 212222110038

import numpy as np
A = np.array([[1, -3],
              [3,  1]])
B = np.array([0, 10])
solution = np.linalg.solve(A, B)
print(solution)
```
## Output:
![Screenshot 2025-04-26 103641](https://github.com/user-attachments/assets/932adcc3-d83c-4832-bb77-9795a8f702c8)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

