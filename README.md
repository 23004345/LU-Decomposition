# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. importing numpy function
2. use numpy and sys packages
3. use nested loops to loop through each row and column
4. end the program
   
   
   

## Program:
(i) To find the L and U matrix
'''
/*
Program to find the L and U matrix.
Developed by: Devesh s
RegisterNumber:23004345 
*/
'''

import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

(ii) To find the LU Decomposition of a matrix
```

/*
Program to find the LU Decomposition of a matrix.
Developed by: Devesh s
RegisterNumber:23004345 
*/
```

import numpy as np

from scipy.linalg import lu_factor, lu_solve

A = np.array(eval(input()))

b = np.array(eval(input()))

lu, piv = lu_factor(A)

x = lu_solve((lu,piv),b

print (x)



## Output:![Screenshot 2023-12-31 123124](https://github.com/23004345/LU-Decomposition/assets/138849203/3277cbae-e948-4284-b150-af7c74e28b09)

![Screenshot 2023-12-31 123058](https://github.com/23004345/LU-Decomposition/assets/138849203/c4a59a6d-1bcc-419e-8ca9-efa3a7a6c908)



![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

