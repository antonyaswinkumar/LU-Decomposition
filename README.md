# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program <br>
2.Import the necessary libraries(numpy,scipy.linalg)<br>
3.Define the matrix using numpy<br>
4.Use lu(),lu_solve(),lu_factor() to get the solutions<br>
5.End the program<br>


## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: Antony Aswin Kumar L
RegisterNumber: 212225040024
'''
```
import numpy as np<br>
from scipy.linalg import lu<br>
A= np.array(eval(input()))<br>
P ,L ,U =lu(A)<br>
print(L)<br>
print(U)<br>
```


(ii) To find the LU Decomposition of a matrix

'''Program to solve a matrix using LU decomposition.
Developed by: Antony Aswin Kumar L
RegisterNumber: 212225040024
'''

## To print X matrix (solution to the equations)

```
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv =lu_factor(A)
x=lu_solve ((lu,piv) , b)
print(x)

```

## Output:

(i) to find the L and U matrix:

<img width="1158" height="777" alt="Screenshot 2026-02-12 182858" src="https://github.com/user-attachments/assets/642831cb-48e2-4c7c-ae73-18d66c9dd2a2" />


(ii) to find the solution using LU decomposition

<img width="948" height="707" alt="Screenshot 2026-02-12 183036" src="https://github.com/user-attachments/assets/4e8c7de7-30b3-4651-ba22-f9cbd47ebb79" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

