# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Define or input the square matrix for which eigenvalues and eigenvectors are to be calculated.
### Step 2: Use the numpy library for efficient numerical computations.
### Step 3: Apply numpy.linalg.eig() to the matrix.
### Step 4: Print or return the computed eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: ROHITH J
#RegisterNumber: 212224230232

import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
e_values,e_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors))

```

## Output:
![alt text](<Screenshot 2025-05-10 232324.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
