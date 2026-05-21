# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: UDHAYDHARSHAN S 
#RegisterNumber: 212225230286
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array([[1, 2, 3],
              [3, 6, 9]])

solution = np.linalg.matrix_rank(a)

print(solution)
```
## Output:
<img width="1057" height="554" alt="image" src="https://github.com/user-attachments/assets/bca5f4bc-b1f8-40d3-8fa9-214dbd499172" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

