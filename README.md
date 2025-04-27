![image](https://github.com/user-attachments/assets/798b3de0-8675-426d-a906-762f64173a33)# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Sanjeev A
#RegisterNumber: 212224230246

import numpy as np
matrix = np.array([[2, -3, 0],[2, -5, 0],[0, 0, 3]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```
## Output:
![Screenshot 2025-04-27 181222](https://github.com/user-attachments/assets/dcec2f6a-3dcd-4a76-81a3-48b633ab2d23)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
