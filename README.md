# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to use the bulit- in functions for calculation
### Step 2: prepare the list from each inverse of matrix and assign in np.array() 
### Step 3:using the np.linalg.matrix_rank() ,we can find the rank of the matrix 
### Step 4:End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: B.venkata bharadwaj
#RegisterNumber:22003979
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
B=np.linalg.inv(A)
print(B)
```
## Output:
![model](/invers-of-matrix.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

