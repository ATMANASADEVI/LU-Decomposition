# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program and import the required libraries (NumPy and SciPy).
2.Define the matrix using NumPy.
3.Use lu() to perform LU decomposition and display the lower and upper triangular matrices.
4.Use lu_factor() and lu_solve() to factorize the matrix and solve the system of equations.
5.Display the solution and end the program.
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Manasa devi AT
RegisterNumber: 212224110036
'''

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
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
Developed by: Manasa devi AT
RegisterNumber: 212224110036
'''

# To print X matrix (solution to the equations)
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,p=lu_fa
ctor(A)
x=lu_solve((lu,p),B)
print(x)

```

## Output:
i)<img width="1477" height="950" alt="image" src="https://github.com/user-attachments/assets/9c94df59-aa29-4720-8de3-efb44af179cd" />
ii)<img width="1425" height="898" alt="image" src="https://github.com/user-attachments/assets/2fdcd59c-bf6d-4e29-ade1-1f451801c492" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
