# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program.
### Step 2: Import the NumPy library and define the given matrix.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and the corresponding eigenvectors and stop the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: NARENDRA KRISHNAN KS 
#RegisterNumber: 212225240096
import numpy as np
A = np.array([[2, 2],
              [1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are",eigenvectors)


```

## Output:
<img width="1383" height="174" alt="image" src="https://github.com/user-attachments/assets/7e4d2ccf-094b-4d73-b3d4-4cd25d08627e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
