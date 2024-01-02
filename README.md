# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program

## Program:
(i) To find the L and U matrix
```'''Program to find L and U matrix using LU decomposition.
Developed by: VIGNESH M
RegisterNumber: 23014020
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```'''Program to solve a matrix using LU decomposition.
Developed by: VIGNESH M
RegisterNumber: 23014020
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

## Output:
![image](https://github.com/vigneshvickyu/LU-Decomposition/assets/151948835/be119f1c-8a41-40b4-b242-19064ffb1a62)
## Output:
![image](https://github.com/vigneshvickyu/LU-Decomposition/assets/151948835/545d225c-e1d8-4dad-a05c-7a509afbd462)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

