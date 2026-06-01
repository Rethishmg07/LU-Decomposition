# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

/*
Program to find the L and U matrix.
Developed by: Anbuselvan J
RegisterNumber: 212225230015
*/
```
(ii) To find the LU Decomposition of a matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
/*
Program to find the LU Decomposition of a matrix.
Developed by: Anbuselvan J
RegisterNumber: 212225230015
*/
```

## Output:
<img width="1210" height="551" alt="Screenshot 2026-06-01 213920" src="https://github.com/user-attachments/assets/979380ea-f800-4025-9a1a-cd6bba49d0b4" />
<img width="1148" height="286" alt="Screenshot 2026-06-01 214438" src="https://github.com/user-attachments/assets/359af66c-86ac-49d2-9dd8-64f3e4c53f11" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

