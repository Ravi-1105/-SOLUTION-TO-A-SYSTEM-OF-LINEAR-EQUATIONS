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
#Developed by: Ravivarman G S
#RegisterNumber: 212223100044

import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
res=np.linalg.solve(A,B)
print(res)
```
## Output:
![image](https://github.com/ArchanaSharikalHarinarayanan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/139841688/f16bd490-e855-445b-9fcb-06dc18fc2617)
![image](https://github.com/ArchanaSharikalHarinarayanan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/139841688/f01e9268-23a7-448c-9ccf-c300cbd568db)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

