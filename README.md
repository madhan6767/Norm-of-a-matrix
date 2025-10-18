# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 25018397
# Developed By: madhan m
# 1-Norm of a Matrix
import numpy as np
matrix = np.array(eval(input()))
norm = np.max(np.sum(np.abs(matrix), axis = 0))
print(norm)
# 2-Norm of a Matrix
import numpy as np
matrix = np.array(eval(input()))
norm = np.linalg.norm(matrix, 2)
print(round(norm, 2))
# Infinity Norm of a Matrix
import numpy as np
matrix = np.array(eval(input()))
norm = np.max(np.sum(np.abs(matrix), axis = 1))
print(norm)
```
## Output:
### 1-Norm of a Matrix
<img width="727" height="244" alt="image" src="https://github.com/user-attachments/assets/816733f8-ab07-495e-9a6a-d0c1f05e0267" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="595" height="293" alt="image" src="https://github.com/user-attachments/assets/cafc3d54-496b-4c06-a099-b179b9179458" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="655" height="218" alt="image" src="https://github.com/user-attachments/assets/bd33fc9a-0dc9-4ae4-8515-5d9a3e6b7837" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
