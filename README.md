# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
import numpy as np

from scipy.linalg import lu

a=np.array(eval(input()))

P,L,U=lu(a)

print(L)

print(U)

```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np

from scipy.linalg import lu factor, lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu,pivot= lu_factor(A)

x=lu_solve((lu,pivot),B)

print(x)
```

## Output:
![lu decomposition]()
![WhatsApp Image 2026-02-07 at 08 41 22](https://github.com/user-attachments/assets/8a8271e7-eed5-4005-be8b-73cd532a9ff1)

![WhatsApp Image 2026-02-07 at 08 41 22 (1)](https://github.com/user-attachments/assets/1adc4444-1512-4fab-82f0-fee2b3b6a45a)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

