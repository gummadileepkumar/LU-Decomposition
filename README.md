# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np.
2. And import lu.
3. Take input from user.
4. print l and u matrix.

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: Gumma Dileep Kumar
RegisterNumber:22007129 
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: Gumma Dileep Kumar
RegisterNumber:22007129 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))

lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:



![LU_output1](https://user-images.githubusercontent.com/118707761/211965073-69e68473-9e18-470c-8d80-76377ed57b7f.png)



![LU_output2](https://user-images.githubusercontent.com/118707761/211965097-534799c5-9059-4569-a1a8-c04efe161986.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

