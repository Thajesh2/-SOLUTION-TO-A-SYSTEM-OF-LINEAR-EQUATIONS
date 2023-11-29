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
#Developed by: thajesh k
#RegisterNumber: 23004042
 
import numpy as np
A = np.array([[1,3],[2,5]])
B = np.array([5,-3])
solution=np.linalg.solve(A,B)
print(solution)
```
## Output:
![image](https://github.com/Thajesh2/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/139841959/1054328c-a58a-4429-864f-bb91d17b0b35)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

