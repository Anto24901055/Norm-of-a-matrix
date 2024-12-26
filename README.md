# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm 1:
	1. Get the input matrix using np.array()   
    2. Find the 1-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Algorithm 2:
    1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Algorithm 3:
    1. Get the input matrix using np.array()   
    2. Find the infinity norm of the matrix using np.linalg.norm(arr,np.inf)
	3. Print the norm of the matrix in two decimal places.
    
## Program:
```Python
# Register No: 24901055
# Developed By: ANTO WILLIAMS S
# 1-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)
    




# 2-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(f"{result:.2f}")
    




# Infinity Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)




```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-12-26 143350](https://github.com/user-attachments/assets/36d1c706-e1aa-49f1-ae33-89897ee8d7ad)

### 2-Norm of a Matrix

![Screenshot 2024-12-26 143412](https://github.com/user-attachments/assets/b8b49bf0-da0b-4c5e-9307-2e76fd67fe10)

### Infinity Norm of a Matrix

![Screenshot 2024-12-26 182219](https://github.com/user-attachments/assets/9c142b3e-4b75-4e03-9217-fb2c495b468b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
