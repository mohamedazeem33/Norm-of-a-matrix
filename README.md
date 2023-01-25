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
# Register No:22007405
# Developed By:MOHAMED AZEEM N
<br>
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

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

![Screenshot (21) new](https://user-images.githubusercontent.com/121040764/214539515-9b683f84-55e7-4e03-99a5-6284d9402dad.png)

### 2-Norm of a Matrix

![Screenshot (22) new](https://user-images.githubusercontent.com/121040764/214539571-d212aeab-a293-42a8-bdd2-02f29f963bc2.png)

### Infinity Norm of a Matrix

![Screenshot (23) new](https://user-images.githubusercontent.com/121040764/214539681-4892098f-48fc-4f9f-973b-b416fdfc4465.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
