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
# Register No     : 212224230010
# Developed By    : AJAY S
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
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
<br>
<br>
<br>

![Screenshot 2025-05-13 200037](https://github.com/user-attachments/assets/9c5b0c2e-a588-4a5d-a874-b6d5df0b5ea7)

### 2-Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2025-05-13 200059](https://github.com/user-attachments/assets/ed11293a-d4d2-47a8-a1ad-d40cd1e38a80)

### Infinity Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2025-05-13 200122](https://github.com/user-attachments/assets/4e9c7805-07f5-434d-bd0b-87ad2acd520c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
