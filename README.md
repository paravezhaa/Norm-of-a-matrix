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
# Developed By: Paravezhaa M
# Register No: 212225040466
```
```python
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```python
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```python
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```


## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="587" height="300" alt="image" src="https://github.com/user-attachments/assets/c23d0937-c951-41cf-a350-e7ee6eea0400" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="537" height="347" alt="image" src="https://github.com/user-attachments/assets/8e5bf231-20cb-4545-9725-9d431c5d934f" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="585" height="305" alt="image" src="https://github.com/user-attachments/assets/9b4cbf2b-7e0e-4ca2-be40-f0e475e20da4" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
