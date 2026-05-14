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


1.Understand the equations
The given system is:
  x−3y=0,3x+y=10

2.Solve the equations manually
From the first equation:
  x=3y

3.Substitute into the second equation:
3(3y)+y=10⇒9y+y=10⇒10y=10
y=1


4.Assign values in the program
x=3y=3

## program:
#Program to find the solution for the given linear equations.
#Developed by: Bhavankumar.P
#RegisterNumber: 212225240026
```
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
solution=np.linalg.solve(a,b)
print(solution)
```


## Output:
<img width="948" height="196" alt="Screenshot 2026-05-14 103933" src="https://github.com/user-attachments/assets/557b08cd-9c86-4c8c-af5c-2cff8d2e1119" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

