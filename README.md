# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Imort the library numpy as np 
### Step 2: Assign the matrix vlues to the variable using array function
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End of the program

## Program:
```
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
val,vec=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(val,vec))
```
## Output:
![Screenshot 2024-12-01 142627](https://github.com/user-attachments/assets/8297d74f-2787-4435-bfb2-930c1cbc13da)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
