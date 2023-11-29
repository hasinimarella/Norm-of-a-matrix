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
# Register No:MARELLA HASINI
# Developed By:23012757
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix=("{:.2f}".format(ans))
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))


# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
![OUTPUT](Norm-of-matrix.png)

### 2-Norm of a Matrix
![OUTPUT](2-Norm-of-matrix.png)

### Infinity Norm of a Matrix
![OUTPUT](<infinity of matrix.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
