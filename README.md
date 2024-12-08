# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy model to use the built-in-functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Hashini R
#RegisterNumber:24900728
import numpy as np
matrix=np.array([[4,2],[2,4]])
e_value,e_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(e_value,e_vectors))
```

## Output:
![Screenshot from 2024-12-08 10-41-04](https://github.com/user-attachments/assets/b9290ccc-76d5-40af-9f4c-1ea2ad78a0c3)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
