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
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))
'''



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/prathyusharavi/Norm-of-a-matrix/assets/147474424/42615170-ded2-4ba6-8974-c6ecbb76a391)



### 2-Norm of a Matrix

![image](https://github.com/prathyusharavi/Norm-of-a-matrix/assets/147474424/dab7a9d7-37ec-4227-bc67-55c85b4c21e1)



### Infinity Norm of a Matrix


![image](https://github.com/prathyusharavi/Norm-of-a-matrix/assets/147474424/f14faab9-d354-47d4-ae82-b390fc11ee47)






## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
