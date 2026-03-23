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
'''Program to find L and U matrix using LU decomposition.
Developed by: VIKASH S
RegisterNumber: 212225230302
'''

import numpy as np
from scipy.linalg import lu
m = eval(input())
p,l,u = lu(m)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: VIKASH S
RegisterNumber: 212225230302
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]='1'

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv= lu_factor(A)
result = lu_solve((lu,piv),B)
print(result)
```

## Output:
![lu decomposition]()
<img width="583" height="512" alt="image" src="https://github.com/user-attachments/assets/282236ed-2c0d-47b5-a546-5c297c51e78a" />

<img width="452" height="383" alt="image" src="https://github.com/user-attachments/assets/eb39c7aa-8893-4ecf-bbba-b35799e8835d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

