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
# Register No:212223100036
# Developed By:NAGALAPURAM HASIF
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:NAGALAPURAM HASIF
RegisterNumber: 212223100036
'''
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
![image](https://github.com/user-attachments/assets/e29cf43c-cab8-40df-800d-e5b0c60c6168)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/8aa2a3b2-11a8-4fb2-a64e-0f753f805cc3)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/a2672925-87b0-4234-99e7-cc6b59bfb5f0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
