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
List the values in array.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the Eigen values and vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: CHAITANYA P S
#RegisterNumber:212222230024
import numpy as np
A=np.array([[4,2],[2,4]])
values,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector)) 
```

## Output:
![image]![Screenshot 2023-04-03 112540](https://user-images.githubusercontent.com/119392724/229423359-222ba97b-09ed-44ce-8c30-feb46f74e4fe.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
