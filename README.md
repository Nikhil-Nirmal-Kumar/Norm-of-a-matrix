# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm, 1-norm, inf-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212225230201
# Developed By: Nikhil Nirmal Kumar
# 1-Norm of a Matrix
#Program to find 1-norm of a matrix.
#Developed by: Nikhil Nirmal Kumar
#RegisterNumber: 212225230201
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: Nikhil Nirmal Kumar
#RegisterNumber: 212225230201
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
#Program to find inf-norm of a matrix.
#Developed by: Nikhil Nirmal Kumar
#RegisterNumber: 212225230201
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1074" height="853" alt="image" src="https://github.com/user-attachments/assets/11e00541-e61c-4e6d-8743-2e99fbdc80b8" />


### 2-Norm of a Matrix
<img width="1036" height="861" alt="image" src="https://github.com/user-attachments/assets/c46653c8-6b3c-4985-9912-f45adce519d3" />


### Infinity Norm of a Matrix
<img width="1170" height="836" alt="image" src="https://github.com/user-attachments/assets/6e412fdb-f017-4768-82a3-ccee6d77a020" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
