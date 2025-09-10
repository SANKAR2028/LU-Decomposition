# LU Decomposition 
```
NAME: SANKAR S
DEPT: B.E/CSE
REG NO: 212224040291
```
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
import numpy as np

Step 2:
from scipy package import lu

Step 3:
get input from the user

Step 4:
print result 

## Program:
(i) To find the L and U matrix
```

import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix

```

import numpy as np
from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot = lu_factor(A)
result=lu_solve((lu,pivot),B)
print(result)


```
## Output:

![alt text](1.png)
![alt text](2.png)
![alt text](3.png)
![alt text](4.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

