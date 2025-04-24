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


#Developed by: Venkata Mohan N

#RegisterNumber:212224230298

import numpy as np

A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]

B=np.array([-9,4,-1])

C=np.linalg.solve(A,B)

print(C)
```

## Output:

![image](https://github.com/user-attachments/assets/f3fc11eb-8ba1-4d7d-b9bf-f8c91ae40449)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

