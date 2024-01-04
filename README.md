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
# Register No:Karsa varthan R.R
# Developed By:23003628
# 1-Norm of a Matrix

Program to find 1-norm of a matrix.
Developed by:Karsha varthan R.R
RegisterNumber:23003628
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix

Program to find 2-norm of a matrix.
Developed by:Karsa varthan R.R
RegisterNumber:23003628
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix

Program to find the infinity of a matrix.
Developed by:Karsa varthan R.R
RegisterNumber:23003628
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-01-04 153203](https://github.com/Karsavarthan/Norm-of-a-matrix/assets/139841970/d612daf4-f15c-4896-bca7-934cd272b907)

<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2024-01-04 153216](https://github.com/Karsavarthan/Norm-of-a-matrix/assets/139841970/966d2409-c937-4f38-b1bb-15925a808431)

<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2024-01-04 153227](https://github.com/Karsavarthan/Norm-of-a-matrix/assets/139841970/c04b99a6-40e0-4de6-95bc-3bf13be48c0c)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
