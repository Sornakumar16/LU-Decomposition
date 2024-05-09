# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. step1: Define the package as scipy.linalg import lu

2. step2: Get input from user and print L and U matrix by 'print'

3. step3: Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4. step4: print the variable 'X'

5. step5: End the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: #sornakumar.s
RegisterNumber: #212223230210
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:#sornakumar.s
RegisterNumber:#212223230210
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
B=np.array([4,5,7])
X=np.linalg.solve(a,B.T)
print(X)
```

## Output:

![image](https://github.com/Sornakumar16/LU-Decomposition/assets/138849327/0dac7337-cef5-4ad5-9398-9fca6c0eab00)
![image](https://github.com/Sornakumar16/LU-Decomposition/assets/138849327/f8900b77-5139-46cc-8c6e-f3a9ed8baaf1)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

