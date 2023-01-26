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
# Register No:22006940
# Developed By:K SAGAR KRISHNA
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# 2-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Screenshot from 2023-01-26 15-31-10](https://user-images.githubusercontent.com/121165786/214809050-576a8875-25b4-4125-81e7-47119b298b66.png)


### 2-Norm of a Matrix
![Screenshot from 2023-01-26 15-31-25](https://user-images.githubusercontent.com/121165786/214809087-5235836d-1b69-4cb6-a75b-d38c82fb9dd7.png)


### Infinity Norm of a Matrix
![Screenshot from 2023-01-26 15-31-44](https://user-images.githubusercontent.com/121165786/214809113-5461d400-646d-4fa6-aa58-8dd07c336ca7.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
