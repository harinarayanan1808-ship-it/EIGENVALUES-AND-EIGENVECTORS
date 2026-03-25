# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HARINARAYANAN.A
#RegisterNumber:212225230090
import numpy as np
matrix=([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eig_value,eig_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_value,eig_vector))
```

## Output:
<img width="1351" height="855" alt="Screenshot 2026-02-10 141302" src="https://github.com/user-attachments/assets/36f6124b-ed4f-4e0a-b3db-241cdc0a68ca" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
