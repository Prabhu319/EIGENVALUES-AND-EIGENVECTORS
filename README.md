# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculations.

Step 2:
Prepare the lists from each equations and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
end the program

#Developed by: prabanjan.m
#RegisterNumber: 24900428
## Program:
```
import numpy as np
A=[2,-3,0],[2,-5,0],[0,0,3]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2024-12-03 110325](https://github.com/user-attachments/assets/58dee21b-46ad-467b-bbdb-e09a2c5c36b3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
