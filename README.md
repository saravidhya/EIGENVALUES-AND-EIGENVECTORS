# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:

```
#Program to 
#Developed by: Vidhiya Lakshmi S
#Reference number: 212223230238

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))

```

## Output:
![Screenshot 2024-03-26 144304](https://github.com/saravidhya/EIGENVALUES-AND-EIGENVECTORS/assets/87062069/182b49b7-9f11-440e-9031-26c752c1006e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
