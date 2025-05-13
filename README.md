# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Input Matrix A (square matrix).
### Step 2: Check: Compute the determinant of A.f it is zero, print that the matrix is non-invertible and stop.
### Step 3: Compute: If the determinant is non-zero, use np.linalg.inv(A) to compute the inverse.
### Step 4: Output: Print the inverse matrix.

## Program:

~~~
#Program to find the rank of a matrix.
#Developed by:JOTHIMANI P 
#RegisterNumber:212224230108


import numpy as np
A=[[1,2,3],[3,6,9]]
solution=np.linalg.matrix_rank(A)
print(solution)
~~~

## Output:

![image](https://github.com/user-attachments/assets/7febbcbd-68db-40ec-9e9b-cb29103c762c)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
