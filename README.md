# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:'''import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))'''

## Output:
<img width="1308" height="746" alt="{BE78E842-B7F2-49C1-AC11-B11ED7C16916}" src="https://github.com/user-attachments/assets/c1e7437f-19cf-4efe-92ca-ad6892896045" />
<img width="1337" height="359" alt="{48F45810-B69B-4D12-ADC9-04C69F3DB989}" src="https://github.com/user-attachments/assets/849bbaa8-ed63-426f-be62-7c45bb1537b1" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
