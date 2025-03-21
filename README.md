# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. from scipy package import lu
3. Get input from the user
4. Print the result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: V.Shriyha
RegisterNumber: 212224230267
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: V.Shriyha
RegisterNumber: 212224230267
*/
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

![Screenshot 2025-03-21 142321](https://github.com/user-attachments/assets/57bfce9c-97e2-4919-95bd-5ae87bed9a7c)
![Screenshot 2025-03-21 142335](https://github.com/user-attachments/assets/57b8a01d-fa30-4df5-8751-ca49d62d3f94)
![Screenshot 2025-03-21 142255](https://github.com/user-attachments/assets/abd14f4d-72ee-4294-8b44-583ea6587d35)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

