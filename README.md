# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```

Program to find the eigen values and eigen vectors.
Developed by: B Prabhanjan
RegisterNumber: 212225040305

import numpy
a = numpy.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b,c = numpy.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")

```
## Output:

![alt text](<Screenshot 2026-03-23 220813.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
