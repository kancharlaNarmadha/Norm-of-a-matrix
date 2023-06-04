# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Algorithm

1. Get the input matrix using np.array()   

2.Find the 2-norm of the matrix using np.linalg.norm()

3. Print the norm of the matrix in two decimal places.

## Program:


 Register No:212222110016
 Developed By:KANCHARLA NARMADHA
 
# 1-Norm of a Matrix
```
import numpy as np
array=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```




# 2-Norm of a Matrix
```
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```



# Infinity Norm of a Matrix
```
import numpy as np
array=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


## Output:
### 1-Norm of a Matrix

![MAT OUTPUT 7 1](https://github.com/kancharlaNarmadha/Norm-of-a-matrix/assets/119559316/bba30d35-e72d-4ded-88c8-c6df5ecf8afc)



### 2-Norm of a Matrix


![MAT OUTPUT 7 2](https://github.com/kancharlaNarmadha/Norm-of-a-matrix/assets/119559316/301b78ff-5aee-40c7-98a5-7d1be4e97bd6)



### Infinity Norm of a Matrix

![MAT OUTPUT 7 3](https://github.com/kancharlaNarmadha/Norm-of-a-matrix/assets/119559316/53ec57d6-b266-4f92-8cd7-009ec6a3e052)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
