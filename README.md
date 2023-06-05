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
```
# Register No:212222230141
# Developed By:shabreena vincent


import numpy as np:

a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix:

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)




# Infinity Norm of a Matrix:

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)





```
## Output:
### 1-Norm of a Matrix



![nomm1](https://github.com/shabreenavincent/Norm-of-a-matrix/assets/119475721/a60569f4-9b91-4395-98c4-a24b45ec2026)


### 2-Norm of a Matrix


![nom2](https://github.com/shabreenavincent/Norm-of-a-matrix/assets/119475721/47693fba-5418-4860-a32b-20c105cf4e89)




### Infinity Norm of a Matrix



![nom3](https://github.com/shabreenavincent/Norm-of-a-matrix/assets/119475721/a5949326-4757-4fa9-a45a-37abf69ac696)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
