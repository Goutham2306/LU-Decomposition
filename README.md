# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Use LU decomposition to factorize the coefficient matrix A into two matrices L(lower triangular) and U (Upper Triangular)

2.Solve for Y in LY=B

3.Solve for X in UX=Y

4.The solution matrix X contains the values of the variables that satisfies the system of linear equations. 

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Goutham.K  
RegisterNumber:23008975

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Goutham.K
RegisterNumber: 23008975

from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:

(i)
![image](https://github.com/Goutham2306/LU-Decomposition/assets/138971154/fd64d832-7cd1-44b5-b0f4-b5a22a72a2dd)

(ii)

![image](https://github.com/Goutham2306/LU-Decomposition/assets/138971154/8b1b9962-3feb-4ac0-a355-f822bd05387c)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

