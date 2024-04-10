# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
### Program to find the eigen values and eigen vectors.
### Developed by: Kanagavel.A.K
### RegisterNumber: 212223230096
```Python
import numpy as np
A = [[2,2],[1,3]]
Eigen_value, Eigen_vector = np.linalg.eig(A)
print("Eigen values are",Eigen_value,"and Eigen Vectors are",Eigen_vector)
```

## Output:
![Screenshot 2024-04-10 231017](https://github.com/KanagavelAK/EIGENVALUES-AND-EIGENVECTORS/assets/151514454/27ac3d36-af44-49e0-8e00-a91ac7ca15da)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
