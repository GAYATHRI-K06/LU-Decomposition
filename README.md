# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. ## STEP1:
Import Libraries:
   - Import the NumPy library as np.

2. ## STEP2:
Input Matrix:
   - Take a matrix as input from the user.
3. ## STEP3:
 LU Decomposition:
   - Use the LU decomposition function to decompose the input matrix into three matrices: P , L , and U 
4. ## STEP4:
Print Matrices:
   - Print the lower triangular matrix (L) and the upper triangular matrix (U).
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: GAYATHRI.K
RegisterNumber: 23013439
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=  lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: GAYATHRI.K
RegisterNumber: 23013439
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

*/
```

## Output:
![](<Screenshot 2023-12-14 155332.png>)
![Alt text](<Screenshot 2023-12-14 155403.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

