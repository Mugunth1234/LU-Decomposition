# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: M.Mugunthan
RegisterNumber: 24005593
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor ,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
/*
Program to find the LU Decomposition of a matrix.
Developed by: M.Mugunthan
RegisterNumber: 24005593
*/
```

## Output:
![lu decomposition]()
![Screenshot 2024-11-27 225501](https://github.com/user-attachments/assets/a45deac4-677f-4290-9959-de1130c7842b)
![Screenshot 2024-11-27 225519](https://github.com/user-attachments/assets/20570c88-1326-4157-9c03-d5f222b529b4)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

