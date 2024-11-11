# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step-1
Define the package as scipy.linalg import lu.

step-2
Get input from user and print L and U matrix by 'print' .

step-3
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

step-4
print the variable 'X'

Step-5
End the program

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Kamalesh y
RegisterNumber: 24004024

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Bhuvaneshwaran H
RegisterNumber: 212223240018

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![Screenshot 2024-11-11 093524](https://github.com/user-attachments/assets/f6ae3345-51e0-4b7b-a7e1-449158dc2d15)
![Screenshot 2024-11-11 095538](https://github.com/user-attachments/assets/f3b13e2c-5bd0-4127-88ba-1229898f3b38)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

