# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
step1 : Import the NumPy library using import numpy as np.
Step 2: Define the matrix using a NumPy array.
Step 3: Use the np.linalg.inv() function to find the inverse of the matrix.
Step 4: Display the inverse matrix using the print() function. 

## Program:
#Program to find the inverse of a matrix.
#Developed by:risitha.s
#RegisterNumber: 212225240119

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
## Output:
<img width="1392" height="1130" alt="image" src="https://github.com/user-attachments/assets/91949560-534f-4256-bc6e-a8590c99681d" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

