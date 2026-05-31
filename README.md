# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[1,0,3],
             [-1,2,-2],
             [2,3,-1]])

inv = np.linalg.inv(A)

print(inv)
```
## Output:
<img width="1920" height="1080" alt="Screenshot 2026-05-31 163844" src="https://github.com/user-attachments/assets/ce9ce8e8-8b29-487c-9b85-c1c511ee85a4" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

