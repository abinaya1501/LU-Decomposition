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
``` python
#Program to find L and U matrix using LU decomposition.
#Developed by: ABINAYA.A 
#RegisterNumber: 24900474 

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
``` python
#Program to solve a matrix using LU decomposition.
#Developed by: ABINAYA.A
#RegisterNumber: 24900474


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition]()
![alt text](<exp05 i.png>)
![alt text](<exp 05 ii.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

