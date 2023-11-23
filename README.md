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
#Developed by: s v shadhanashree
#RegisterNumber:23013434
import numpy as np
A=[[1,-3],[3,1]]
B=[0,10]
C=np.linalg.solve(A,B)
print(C)

```

## Output:
![output](./solution.png)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

