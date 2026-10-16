# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation
### Step 2:Prepare the lists from each linear equations and assign in np.array() 
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4:End the program  

## Program:
#Program to find the inverse of a matrix.
#Developed by: sumanth RK
#RegisterNumber:26017294
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
r=np.linalg.inv(A)
print(r)
## Output:<img width="1164" height="245" alt="Screenshot 2026-10-16 085504" src="https://github.com/user-attachments/assets/60111ded-a615-4598-a14c-8ab2b7158f9f" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

