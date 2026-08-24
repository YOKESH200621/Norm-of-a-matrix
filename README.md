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
# Register No: 212224230313
# Developed By: YOKESH I
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: YOKESH I
RegisterNumber: 212224230313
'''


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
<br><img width="1431" height="963" alt="image" src="https://github.com/user-attachments/assets/57add996-5cef-42e3-90a0-95c5be1fd853" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<br><img width="1407" height="935" alt="image" src="https://github.com/user-attachments/assets/ab6c5b58-f61f-4b4f-a06b-c355b02bc3ec" />

<br>

### Infinity Norm of a Matrix
<br>
<br>
<br><img width="1414" height="967" alt="image" src="https://github.com/user-attachments/assets/302383b1-4470-4017-927a-da49da48da67" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
