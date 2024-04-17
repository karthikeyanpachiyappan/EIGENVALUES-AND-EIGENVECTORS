# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import  the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the list for each linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(), we can find the eigen value and eigen vector of the given matrix.
### Step 4: 
End the program. 

## Program:
```
Developed by: Karthikeyan P
RegisterNumber:212223230102
```
```
import numpy as np
matrix=np.array([[4,2],[2,4]])
eigval,eigvect=np.linalg.eig(matrix)
print("Eigen values are",eigval,"and Eigen Vectors are",eigvect)
```
## Output:
![Screenshot 2024-04-17 104422](https://github.com/karthikeyanpachiyappan/EIGENVALUES-AND-EIGENVECTORS/assets/155143878/79631277-6543-4b9f-b814-efc4f27bea68)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
