# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End of program

## Program:
    import numpy as np
    a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
    eigenvalues,eigenvectors=np.linalg.eig(a)
    print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)

## Output:
![image 1](<Screenshot 2024-12-13 182333.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
