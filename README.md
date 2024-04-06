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
```python
#Developed By: Kannan.S
#Register No: 212223230098
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)
```


# 2-Norm of a Matrix
```python
#Developed By: Kannan.S
#Register No: 212223230098 

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_mat="{:.2f}".format(ans)
print(norm_mat)
```



# Infinity Norm of a Matrix
```python
#Developed By: Kannan.S
#Register No: 212223230098

import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)
```





## Output:
### 1-Norm of a Matrix
![unit 3 ex 7(i)](https://github.com/Kannan-S-coder/Norm-of-a-matrix/assets/147120710/7bafbc6f-9b31-41b5-9391-fbfe19d3aad0)


### 2-Norm of a Matrix
![unit 3 ex 7(ii)](https://github.com/Kannan-S-coder/Norm-of-a-matrix/assets/147120710/ae53776f-ad4b-42f3-905f-c657c0be1045)


### Infinity Norm of a Matrix
![unit 3 ex 7(iii)](https://github.com/Kannan-S-coder/Norm-of-a-matrix/assets/147120710/edf7bbfc-907e-40dd-b756-a0e0452144f9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
