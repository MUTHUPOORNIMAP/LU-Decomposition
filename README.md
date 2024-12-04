# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1st Program Algorithm:
Step 1:Import the numpy module to use the built-in functions for calculation.
Step 2:Use scipy.linalg() to import and perfrom  LU decomposition.
Step 3:Get the input from the user using np.array().
Step 4:Perform LU decomposition.
Step 5: Print L and U matrices and end the program.

2nd Program Algorithm:
Step 1:Import the numpy module to use the built-in functions for calculation.
Step 2:Import lu_factor,lu_solve using scipy.linalg()
Step 3:Input the matrices A and B using np.array()
Step 4:Use lu.factor() to perform Lu factorisation
Step 5:Using lu.solve() solve the system
Step 6: Print and end the program

## Program:
(i) To find the L and U matrix
```
import numpy as np 
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
/*
Program to find the L and U matrix.
Developed by: Muthu Poornima.P
RegisterNumber:24006054 
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Muthu Poornima.P
RegisterNumber: 24006054
*/
```

## Output:
![lu decomposition]()
![image](https://github.com/user-attachments/assets/409f8f4b-2184-452e-8e7a-bdfa1bf138a3)
![image](https://github.com/user-attachments/assets/aa8f834b-2c3c-4aaa-ac02-7f2237cba19e)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

