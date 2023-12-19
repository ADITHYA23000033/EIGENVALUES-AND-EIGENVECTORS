# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : importing numpy function
### Step 2: assigning values to the variable in list form
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Using print function print the eigen values

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: ADITHYA V
#RegisterNumber: 23000033
import numpy as np
a=[[4,2],[2,4]]
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
~~~

## Output:

![image](https://github.com/ADITHYA23000033/EIGENVALUES-AND-EIGENVECTORS/assets/148514544/0f6cbd18-3783-4794-84e7-3c6dca162a6f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
