# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: ROSHINI S
RegisterNumber: 212223240142
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: ROSHINI S 
RegisterNumber: 212223240142
'''

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:

![Screenshot 2024-04-07 093523](https://github.com/Roshini2201/LU-Decomposition/assets/154105318/8f860ba7-998f-4051-b41f-7c9e483a0ef2)

![Screenshot 2024-04-07 094001](https://github.com/Roshini2201/LU-Decomposition/assets/154105318/fb5289d0-c5ec-46d8-99cf-6ac366f26faa)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

