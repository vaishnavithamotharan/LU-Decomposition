# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import the numpy module to use built-in functions for calculation
Step 2:
Prepare the list from matrix and assign in np.array()
Step 3:
Use the lu(A) ,we can find the solution
Step 4:
Use the lu_solve,we can find the solution
Step 5:
End the program 

## Program:
(i) To find the L and U matrix

Program to find the L and U matrix.
Developed by: VAISHNAVI T
RegisterNumber: 25017435

```

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To Find the LU Decomposition of a matrix.

Program to find the LU Decomposition of a matrix.
Developed by: VAISHNAVI T
RegisterNumber: 25017435

```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
X=lu_solve((lu,pivot),B)
print(X)
```
## Output:
<img width="1920" height="1080" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/f31488b3-e42c-4255-bce9-43f60a358917" />
<img width="1920" height="1080" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/3cec3977-c413-495b-a14c-1efe6ba02ee3" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

