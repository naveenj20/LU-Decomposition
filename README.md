# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array().
3.  Using the scipy library, we can find the LU Decomposition of the given matrix.
4. End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Naveen Jaisanker
RegisterNumber: 24001290
*/

import numpy as n
from scipy.linalg import lu
x=n.array(eval(input()))
P,L,U=lu(x)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Naveen Jaisanker
RegisterNumber: 24001290
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu, piv), b)
print(X)
```

## Output:
![Screenshot 2024-11-27 193651](https://github.com/user-attachments/assets/e6d7499f-8536-409c-b5ea-0cea2f9d703b)

![Screenshot 2024-11-27 193703](https://github.com/user-attachments/assets/707b511b-3d06-4e62-913d-c50d45335164)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

