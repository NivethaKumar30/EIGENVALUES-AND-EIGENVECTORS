# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

Step1 : To find inverse of a matrix using python programming

Step 2: Import numpy as np.

Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4: Print result

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: K.NIVETHA
#RegisterNumber:22009186

import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![maths 4](https://user-images.githubusercontent.com/119559844/215285822-ffaacf83-4edc-43c7-8eb1-5d4973a27c30.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
