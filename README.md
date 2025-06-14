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

Register No:212224240017

Developed By:Ashish S
```
1-Norm of a Matrix:

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
2-Norm of a Matrix:

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
Infinity Norm of a Matrix:

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:

1-Norm of a Matrix:


![image](https://github.com/user-attachments/assets/c5527402-a14a-4165-a319-21da4c0895ad)


2-Norm of a Matrix:


![image](https://github.com/user-attachments/assets/abd172b9-ead3-4130-b61e-df24d56f1a17)


Infinity Norm of a Matrix:


![image](https://github.com/user-attachments/assets/3417e179-27ff-4261-8358-402e6ee2ee85)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
