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
# 1-Norm of a Matrix
Program to find 1-norm of a matrix.
Developed by: AUGUSTINE J
RegisterNumber: 22009432
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix 
Program to find 2-norm of a matrix. 
Developed by: AUGUSTINE J
RegisterNumber: 22009432
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix
Developed by: AUGUSTINE J
RegisterNumber: 22009432
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![one norm](https://user-images.githubusercontent.com/119404460/214788324-b41036ab-0abc-4af4-9b52-00bd8f0a53de.png)


### 2-Norm of a Matrix
![two ](https://user-images.githubusercontent.com/119404460/214788351-2c1fa53f-1c5a-47aa-85f3-294e76970c83.png)


### Infinity Norm of a Matrix
![three](https://user-images.githubusercontent.com/119404460/214788392-32629e22-b4e5-40b8-b76c-64d35fa1af5a.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
