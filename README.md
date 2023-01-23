# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : 
import numpy matrix
### Step 2: 
get the import matrix
### Step 3: 
find the eigen value
### Step 4:
print the result

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: vaishnavi
#RegisterNumber:22009040
import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![eigen value](https://user-images.githubusercontent.com/118541897/208304488-ac4d8691-cae2-436e-9c7f-245a3f505654.png)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
