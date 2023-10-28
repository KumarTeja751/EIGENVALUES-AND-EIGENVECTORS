# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
+1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built-in functioms for calculation
### Step 2: 
Get the input matrix from the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Kumarteja Naramala
#RegisterNumber: 23003525
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {0} and Eigen Vectors are {1}".format(values,vectors))
```
## Output:
![Eigen values](https://github.com/KumarTeja751/EIGENVALUES-AND-EIGENVECTORS/assets/144947756/4597d4f8-bdc6-4832-8f69-07f2efed0d71)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
