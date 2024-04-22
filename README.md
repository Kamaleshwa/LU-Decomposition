## LU Decomposition
## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
Hardware – PCs

Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm :
1.Read the elements of augmented matrix into arrays a and b

2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution

5.Find X by solving UX = V by backward substitution

6.Print Array X as the solution
## Program:
(i) To find the L and U matrix
```
## Program to find the L and U matrix.
Developed by: Kamaleshwar kv
RegisterNumber: 212223240063

from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
```
Developed by:kamaleshwar kv
RegisterNumber: 212223240063

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![image](https://github.com/Kamaleshwa/LU-Decomposition/assets/144980199/837b7947-0024-407a-a6c2-236a2aff8772)
![image](https://github.com/Kamaleshwa/LU-Decomposition/assets/144980199/bc660907-4070-4ae7-85b9-37b3005d3f20)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

