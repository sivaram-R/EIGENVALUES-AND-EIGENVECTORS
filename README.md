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
#Developed by: sivaram R
#RegisterNumber:22008680
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![eigen1](https://user-images.githubusercontent.com/121165794/209474583-20bfc22d-cfca-40e9-9766-a4b8e5117728.png)
![eigen 2](https://user-images.githubusercontent.com/121165794/209474599-7e0102a9-7405-463f-ad1a-ee553061c403.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
