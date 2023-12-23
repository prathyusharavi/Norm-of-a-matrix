# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places..
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:23009045
# Developed By:YENUGANTI PRATHYUSHA
# 1-Norm of a Matriximport numpy as np
mat=np.array(eval(input())) 
ans=np.linalg.norm(mat,1)
norm_of_matrix=("{:.2f}".format(ans))
print(norm_of_matrix)

'''
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:YENUGANTI PRATHYUSHA
RegisterNumber: 23009045
'''
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
program to find 3-norm of a matrix
developed by :YENUGANTI PRATHYUSHA
Register number: 23009045
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/prathyusharavi/Norm-of-a-matrix/assets/147474424/b7889559-6de8-4e93-87bf-195d31efab19)


### 2-Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/prathyusharavi/Norm-of-a-matrix/assets/147474424/60abd39b-a4e3-4e69-b37f-2a6f9059368e)



### Infinity Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/prathyusharavi/Norm-of-a-matrix/assets/147474424/24ec8f74-4ae3-47c3-b824-d8c55c7eb85c)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
