# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu,lu_factor,lu_piv
3. Get input from the user as eval(input())
4. Use lu_factor and lu_solve to find LU decomposition
5. print L,U
6. print x
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Ajay J
RegisterNumber: 212224110003
'''
import numpy as np
from scipy.linalg import lu

A = eval(input())

P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Ajay J 
RegisterNumber: 212224110003
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve

A =np.array(eval(input()))
B =np.array(eval(input()))

lu,pivot = lu_factor(A)
result = lu_solve((lu,pivot),B)
print(result)
```

## Output:
<img width="1220" height="928" alt="image" src="https://github.com/user-attachments/assets/513fe34d-20aa-4fab-bea4-f3cdf1826182" />


<img width="1236" height="790" alt="image" src="https://github.com/user-attachments/assets/4669761f-becc-4a1c-ba63-a7aab4791a72" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

