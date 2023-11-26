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
#Developed by: M.suren. 
#RegisterNumber: 23005055.
import numpy as np
A=[[1,-3],[3,1]]
B=[0,10]
C=np.linalg.solve(A,B)
print(C)
```
## Output:
![Screenshot 2023-11-26 210242](https://github.com/Msuren48106/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150503875/08b22db8-d9ff-4941-95e9-2f16b361d81a)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

