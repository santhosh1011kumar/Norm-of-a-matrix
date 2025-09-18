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
# Register No: Santhosh Kumar A
# Developed By: 212224230250


# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix=print("{:.2f}".format(ans))



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="1012" height="934" alt="image" src="https://github.com/user-attachments/assets/1df3eead-3330-46de-b1b6-a1379f5ec30f" />

### 2-Norm of a Matrix
<img width="1079" height="930" alt="image" src="https://github.com/user-attachments/assets/343df77d-4371-4910-8dc3-79706b869283" />

### Infinity Norm of a Matrix
<img width="998" height="834" alt="image" src="https://github.com/user-attachments/assets/bb48c742-5018-4c98-a335-cc812eee4570" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
