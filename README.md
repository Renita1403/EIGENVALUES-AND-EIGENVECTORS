# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End of the Program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Renita Ireen G
#RegisterNumber:25008430

import numpy as np

# Define the matrix
A = np.array([[-2,  2, -3],
              [ 2,  1, -6],
              [-1, -2,  0]])

# Compute eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Print in the expected format
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1419" height="830" alt="Screenshot 2025-12-14 180151" src="https://github.com/user-attachments/assets/234b6e3a-1694-4f36-8e56-c0f467dab791" />
<img width="1274" height="368" alt="Screenshot 2025-12-14 180212" src="https://github.com/user-attachments/assets/0f2e80d4-6018-471c-9fd1-04de62c34c9e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
