# LU Decomposition 
### Name: Anbuselvan.S
### Reference No: 23005959
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for L and U Matrix:
Import the numpy module to use the built-in functions for calculation.
from scipy.linalg import lu
Enter the lists from each linear equations and assign in np.array()
using lu() and store it in three variables
print the L and U Matrix
End the program

## Algorithm for LU Decomposition:
Import the numpy module to use the built-in functions for calculation
from scipy.linalg import lu_factor,lu_solve
Enter the lists from each linear equations and assign in np.array()
Enter the lists from each linear equations and assign in np.array()
using lu_factor() and store it in two variables
using lu_solve(),we can find L and U matrix 7. End the program 

## Program:
(i) To find the L and U matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Anbuselvan.S
RegisterNumber: 23005959
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Anbuselvan.S
RegisterNumber: 23005959
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
c=np.array(eval(input()))
r=lu_factor(a)
sol=lu_solve(r,c)
print(sol)
```

## Output:
![image](https://github.com/anbuselvan1519/LU-Decomposition/assets/139841744/9c35b458-b1ad-47ba-a2d5-5c5b1a9f10ba)
![image](https://github.com/anbuselvan1519/LU-Decomposition/assets/139841744/21abbf39-5a52-4fab-962c-48ce95b2b5a6)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

