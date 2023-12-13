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
#Developed by: saranya.S
#RegisterNumber: 23013399

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
le=np.linalg.solve(a,b)
print(le)

```

## Output:
![Screenshot 2023-12-13 210657](https://github.com/srisrisaranya/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/148516638/34f11218-ae49-496d-9e64-633dc1b902c9)





## Result: 
Thus the solutions for the linear equations are successfully solved using python program

