# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
### Step 1: Start the process.
### Step 2: Input the matrix.
### Step 3: Calculate the 1-norm of the matrix, which is the maximum absolute column sum.
### Step 4: Display the calculated 1-norm value.
### Step 5: End the process.

2. Find the 2-norm of the matrix using np.linalg.norm()
### Step 1: Start the process.
### Step 2: Input the matrix.
### Step 3: Calculate the 2-norm of the matrix, which is the largest singular value 
### Step 4: Display the calculated 2-norm value.
### Step 5: End the process.

3. Print the norm of the matrix in two decimal places.
### Step 1: Start the process.
### Step 2: Input the matrix.
### Step 3: Calculate the infinity norm, which is the maximum absolute row sum of the matrix.
### Step 4: Display the calculated infinity-norm value.
### Step 5: End the process.

## Program:
```
# Register No:212224230040
# Developed By:BOYALAKUNTLA KHAJA RASOOL
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: BOYALAKUNTLA KHAJA RASOOL
RegisterNumber: 212224230040
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print("{:.2f}".format(result))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: BOYALAKUNTLA KHAJA RASOOL
RegisterNumber: 212224230040
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))

# Infinity Norm of a Matrix

'''
Program to find infinity-norm of a matrix.
Developed by: BOYALAKUNTLA KHAJA RASOOL
RegisterNumber: 212224230040
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))


```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/f382436b-2512-4277-866a-bf1b93c3f9ac)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/e9d4ee1b-78b5-439d-b63f-7c4162a07b4b)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/c529eadc-cbd3-4b3d-9661-0ee09538e4bc)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
