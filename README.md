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
Program to find the solution for the given linear equations.
Developed by: Prashanth.K
RegisterNumber:212223230152
import numpy as np
A=np.array(([5,-3,-10],[2,2,-3],[-3,-1,5]))
B=np.array([-9,4,-1])
C=np.linalg.solve(A,B)
print(C)
```

## Output:
![Screenshot 2024-04-06 141525](https://github.com/PRASHANTHRATHI/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145743120/1abf6c4d-705b-44ac-a8c3-a2bf95ec8977)
![Screenshot 2024-04-06 141533](https://github.com/PRASHANTHRATHI/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145743120/4c3176a4-c02c-4a4a-aee2-4b931c2fe966)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

