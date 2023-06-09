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
### 1-Norm of a Matrix
```
Program to find the 1-Norm of a matrix.
Developed by : Alfred A B
register number:212222110002

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
```

### 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: Alfred A B
RegisterNumber: 212222110002

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
```

# Infinity Norm of a Matrix
```
Program to find Infinity norm of a matrix.
Developed by Alfred A B
Register number: 212222110002

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```

## Output:
### 1-Norm of a Matrix
![norm 1](https://github.com/Alfredsec/Norm-of-a-matrix/assets/120621608/33410647-b900-46e0-ab3e-92239c0db0ee)

### 2-Norm of a Matrix
![norm 2](https://github.com/Alfredsec/Norm-of-a-matrix/assets/120621608/52e6c665-8530-449f-8cce-f5ef1c8558e3)

### Infinity Norm of a Matrix
![infinity norm ](https://github.com/Alfredsec/Norm-of-a-matrix/assets/120621608/3eb3c5c1-7908-427f-aa17-fa4a708d49ad)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
