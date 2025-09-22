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
# Register No: SARAVANA KUMAR S
# Developed By: 212224220090
# 1-Norm of a Matrix

'''
program to find the 1-Norm
Developed by: SARAVANA KUMAR S
Register Number:212224220090
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix=print("{:.2f}".format(ans))


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: SARAVANA KUMAR S
RegisterNumber: 212224220090
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

'''
program to find the infinity of a matrix
Developed by: SARAVANA KUMAR S
Register Number : 212224220090
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix

 <img width="499" height="550" alt="Screenshot 2025-09-22 103438" src="https://github.com/user-attachments/assets/e3978308-3b97-4599-ab2c-04ddcf3b830b" />


### 2-Norm of a Matrix

<img width="621" height="579" alt="Screenshot 2025-09-22 103502" src="https://github.com/user-attachments/assets/1d8a46b6-f629-4ca2-822f-3157e40a3d89" />


### Infinity Norm of a Matrix

<img width="557" height="559" alt="Screenshot 2025-09-22 103536" src="https://github.com/user-attachments/assets/93819be7-9f9d-4076-a4f6-e0179361f453" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
