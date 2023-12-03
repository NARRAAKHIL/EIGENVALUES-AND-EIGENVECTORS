# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
tep1 :
Import the numpy module to use the built-in functions for calculation.

Step 2:
Prepare the lists from each equations and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:NARRA AKHIL 
#RegisterNumber:23003406
```
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/NARRAAKHIL/EIGENVALUES-AND-EIGENVECTORS/assets/144979843/ea42097c-5d79-4ca1-a6a2-625806da853a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
