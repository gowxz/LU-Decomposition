## EX:5.LU Decomposition 
## Date:
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built_in function for calculation 
2. Prepare the lists fro each linear equations and assign in np.array()
3. Using the np.linalg.solve(),we can find the solutions
4. End of the program

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:Gowtha S
RegisterNumber:2305002008
```
```
 # To print L and U matrix
 import numpy as np
 from scipy.linalg import lu
 A=np.array(eval(input()))
 P,L,U=lu(A)
 print(L)
 print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by:Gowtham S
RegisterNumber:2305002008 
```
```
# To print L and U matrix
 import numpy as np
 from scipy.linalg import lu_factor,lu_solve
 A=np.array(eval(input()))
 B=np.array(eval(input()))
 lu,piv = lu_factor(A)
 x=lu_solve((lu,piv),B)
 print(x)
```

## Output:
![IMG-20240513-WA0010](https://github.com/gowxz/LU-Decomposition/assets/155504997/b9089a6f-a1ce-4b93-8fea-5dc75979e036)

![IMG-20240513-WA0012](https://github.com/gowxz/LU-Decomposition/assets/155504997/d048de1a-d873-447e-bb3e-6241213c4dcb)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

