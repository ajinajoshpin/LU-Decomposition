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
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: ajina joshpin
RegisterNumber: 23013547
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: ajina joshpin
RegisterNumber: 23013547
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

*/
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/ajinajoshpin/LU-Decomposition/assets/148514578/e33332ec-433b-4389-aa60-55ee3ccc390a)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/ajinajoshpin/LU-Decomposition/assets/148514578/28048c81-76ac-4c85-86e7-d7a2726fcabc)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

