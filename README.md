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
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: JESU SMARTIA A
RegisterNumber: 212223110016
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: JESU SMARTIA A
RegisterNumber: 212223110016
'''
# Type your code here
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
'''
Program to find infinity of a matrix.
Developed by: JESU SMARTIA A
RegisterNumber: 23013932
'''
# Type your code here
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-01-03 053656](https://github.com/jesu-smartia05/Norm-of-a-matrix/assets/148514819/cbc05533-81ef-4185-b3c3-a304b4146467)
### 2-Norm of a Matrix

![Screenshot 2024-01-03 054028](https://github.com/jesu-smartia05/Norm-of-a-matrix/assets/148514819/d2d8c139-168b-4356-ad45-849dfff592f3)
### Infinity Norm of a Matrix

![Screenshot 2024-01-03 054125](https://github.com/jesu-smartia05/Norm-of-a-matrix/assets/148514819/daa9dd9e-6f06-4651-8466-18d198832226)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
