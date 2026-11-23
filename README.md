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

# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
nosm1=np.linalg.norm(a,1)
norm="{:.2f}".format(nosm1)
print(norm)
```


# 2-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,2)
norm="{:.2f}".format(norm1)
print(norm)
```



# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(norm1)
print(norm)

```
## Output:
### 1-Norm of a Matrix
<img width="1277" height="342" alt="image" src="https://github.com/user-attachments/assets/b375dd52-fc50-4ce6-9724-c7cd88827f82" />


### 2-Norm of a Matrix
<img width="1390" height="437" alt="image" src="https://github.com/user-attachments/assets/bee3823f-bf11-4fcb-97ff-5b6b14be4c28" />

### Infinity Norm of a Matrix
<img width="1365" height="332" alt="image" src="https://github.com/user-attachments/assets/aa23e24b-3e09-48f8-abe4-1d995090db3a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
