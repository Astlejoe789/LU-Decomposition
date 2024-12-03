# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu
3. Get input as np.array()
4. Now use the lu() and print the output
## Program:
```
1.
    '''Program to find L and U matrix using LU decomposition.
    Developed by:ASTLE JOE AS
    RegisterNumber: 24004571
    '''
    import numpy as np
    from scipy.linalg import lu
    matrix=np.array(eval(input()))
    piv,l_matrix,u_matrix=lu(matrix)
    print(l_matrix)
    print(u_matrix)
2.
    '''Program to solve a matrix using LU decomposition.
    Developed by: ASTLE JOE AS
    RegisterNumber: 24004571
    '''

    # To print X matrix (solution to the equations)
    import numpy as np
    from scipy.linalg import lu_factor,lu_solve
    matrix=np.array(eval(input()))
    b=np.array(eval(input()))
    x=lu_factor(matrix)
    solution=lu_solve(x,b)
    print(solution)

```
## Output:
![image 1](<Screenshot 2024-12-03 202017.png>)
![image 2](image.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

