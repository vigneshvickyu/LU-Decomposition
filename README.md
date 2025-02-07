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
![Screenshot 2024-01-02 231321](https://github.com/vigneshvickyu/LU-Decomposition/assets/151948835/94cac41b-0ca8-4ef1-bb6a-629782a861f0)
![image](https://github.com/vigneshvickyu/LU-Decomposition/assets/151948835/9c89f0dd-03e2-41b3-a095-efed00327347)






## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

