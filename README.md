# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X'.

## Program:
Developed by  : Sanjay S 

RegisterNumber: 212221243002

(i) To find the L and U matrix
```python
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```python
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a=eval(input())
b=eval(input())
lu,c=lu_factor(a)
x=lu_solve((lu,c),b)
print(x)
```

## Output:
##  L and U matrix:
![image](https://github.com/sanjay5656/LU-Decomposition/assets/115128955/32c17c91-01f0-4cca-8a3f-05ad0d583734)

## LU Decomposition of a matrix:
![image](https://github.com/sanjay5656/LU-Decomposition/assets/115128955/f3848229-ebf6-4f71-81c1-99cca1d9073e)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

