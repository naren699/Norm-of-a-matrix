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

# Register No:24003040

# Developed By:NARENDHIRAN P

# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix= "{:.2f}".format(ans)

print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,2)

norm_of_matrix= "{:.2f}".format(ans)

print(norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,np.inf)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-07 233510](https://github.com/user-attachments/assets/6c4c1de4-9cce-42b7-9472-dbb15aea6c5a)


### 2-Norm of a Matrix
![Screenshot 2024-12-07 233517](https://github.com/user-attachments/assets/88d551f8-dcbc-497e-bfef-d709fd31ea3e)


### Infinity Norm of a Matrix
![Screenshot 2024-12-07 233524](https://github.com/user-attachments/assets/70f6e739-e19f-40b0-b831-95804d7d02d1)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
