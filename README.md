# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Use np.linalg.inv() function to find the inverse of the matrix.
## Algorithm:
### Step 1: Import the NumPy library and create the matrix using np.array().
### Step 2: Use np.linalg.inv() function to find the inverse of the matrix.
### Step 3: Store the inverse matrix in a variable.
### Step 4: Print the inverse matrix using the print() function.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: v.priyadaarshini
#RegisterNumber:212225040317

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])

inverse_matrix = np.linalg.inv(A)

print(inverse_matrix)
```

## Output:
![alt text](<Screenshot 2026-05-14 212335.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

