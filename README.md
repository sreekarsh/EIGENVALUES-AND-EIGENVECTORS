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
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Masina Sree karsh 
#RegisterNumber: 23005860
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
b,vectors=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",vectors)
```
## Output:

![image](https://github.com/sreekarsh/EIGENVALUES-AND-EIGENVECTORS/assets/139841918/24a0fb78-6ef8-463a-b9ea-d1521bc2c432)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
