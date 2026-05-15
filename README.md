# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the required libraries os and numpy.
### Step 2: Set the OpenBLAS thread count to 1 using os.environ["OPENBLAS_NUM_THREADS"]="1".
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Jeensfer Jo
#RegisterNumber: 212225240058
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="1180" height="714" alt="image" src="https://github.com/user-attachments/assets/16395aa3-0984-4a2d-9a91-58d0bd068c7b" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

