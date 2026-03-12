# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Read the input matrix A and (if requried) matrix B.
3. Perform LU decomposition on matrix A to obtain L and U,and use them to solve AX=B
4. Display the matrices L,U and the solution matrix X,then stop


## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: K.KARANKUMAR
RegisterNumber: 212225040171
```
import numpy as np
from scipy.linalg import lu
a=eval(input())
b=np.array(a)
p,l,u=lu(a)
print(l)
print(u)

(ii) To find the LU Decomposition of a matrix
```Program to find the LU Decomposition of a matrix.
Developed by: K.KARANKUMAR
RegisterNumber:212225040171
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()),dtype=float)
B=np.array(eval(input()),dtype=float)
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)


## Output:
<img width="952" height="309" alt="Screenshot 2026-03-12 215715" src="https://github.com/user-attachments/assets/b165be43-f73c-4b23-adca-f5704b29e7f3" />
<img width="949" height="266" alt="Screenshot 2026-03-12 215731" src="https://github.com/user-attachments/assets/c7a81c8b-ecc6-479d-9bbe-8f94e11bfbe1" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

