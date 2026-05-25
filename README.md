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
# Register No:212225240130
# Developed By:S.SAHANA
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
n="{:.2f}".format(ans)
print(n)



# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
n="{:.2f}".format(ans)
print(n)

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
n="{:.2f}".format(ans)
print(n)

```
## Output:
### 1-Norm of a Matrix
<img width="716" height="782" alt="image" src="https://github.com/user-attachments/assets/f453c594-dcb6-4bf7-acf4-636855a18b66" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="693" height="722" alt="image" src="https://github.com/user-attachments/assets/ea691c96-8fd3-4e41-9e7e-432370e6de8a" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="676" height="772" alt="image" src="https://github.com/user-attachments/assets/58a146ea-1757-4562-9e4d-f9f33ca5aeb8" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
