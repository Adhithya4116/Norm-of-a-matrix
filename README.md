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
# Register No:22008747
# Developed By:Adhithyha Perumal.D

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)
```

## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/118707079/215276203-a4771a3f-1b37-4e63-8887-c0193afd521e.png)


### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/118707079/215276237-af281839-82c4-4594-aa8e-c4e6dc26c91b.png)


### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/118707079/215276243-5a0e72a3-acde-4610-aa8d-00eda4c50519.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
