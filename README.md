# LU Decomposition to find L and U matrix

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np.
2. Import lu from scipy.linalg.
3. Declare the array as A.
4. Assign P,L,U (Pivot matrix,L matrix and U matrix) to lu of A.
5. Print L and U.

## Program:

```
#Program to find the L and U matrix.
#Developed by: VASUNDRA SRI R
#RegisterNumber: 212222230168
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:


![screenshot61](https://user-images.githubusercontent.com/119393983/236673377-5abbcd8a-57d0-44e9-8649-c6bc88662056.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

# Using LU Decomposition to solve a matrix

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np.
2. Import lu_factor and lu_solve from scipy.linalg.
3. Get the input of A and B matrix.
4. Assign lu and piv (lu and pivot matrix) to lu_factor of A.
5. Assign X to lu_solve of lu and piv with B and print X.

##Program:
```
#Program to find the LU Decomposition of a matrix.
#Developed by: VASUNDRA SRI R
#RegisterNumber: 212222230168
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=eval(input())
b=eval(input())
lu, piv=lu_factor(A)
x=lu_solve((lu, piv), b)
print(x)
```

## Output:


![lu](https://user-images.githubusercontent.com/119393983/236673515-4d40142e-cc8d-4347-b8cc-411f548b8693.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

