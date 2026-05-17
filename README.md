# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation

2. Prepare the lists from each linear equations and assign in np.array()
 
3. Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: 212225220014
RegisterNumber: K.Ashwin Nehrej
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(np.array(A))
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by:212225220014 
RegisterNumber:K.Ashwin Nehrej 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
B=np.array(eval(input()))
x=np.linalg.solve(A,B)

print(x) 
*/
```

## Output:
(i) To find the L and U matrix
<img width="1257" height="574" alt="image" src="https://github.com/user-attachments/assets/da075d95-97aa-438b-a13d-deb1c47466fc" />


(ii) To find the LU Decomposition of a matrix
<img width="1301" height="312" alt="Screenshot 2026-05-14 153712" src="https://github.com/user-attachments/assets/51c61fed-2831-4b26-93ae-78f18501f588" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

