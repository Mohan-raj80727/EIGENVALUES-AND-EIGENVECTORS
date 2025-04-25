# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Mohan Raj.s
#RegisterNumber:212224100036

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
![image](https://github.com/user-attachments/assets/9eeea740-2210-49cf-95fb-1ee32dd4b504)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
