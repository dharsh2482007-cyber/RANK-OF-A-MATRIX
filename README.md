RANK-OF-A-MATRIX



Aim:

To write a python program to find the rank of a matrix.

Equipment’s required:

Hardware – PCs

Anaconda – Python 3.7 Installation / Moodle-Code Runner

Algorithm:


Step 1:

Import the numpy module and os module to use built-in matrix functions.

Step 2:

Create the matrix using np.array() function.

Step 3:

Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4:

Display the rank of the matrix.

Program:

#Program to find the rank of a matrix.


#Developed by: P.PRIYADHARSHINI


#RegisterNumber:212225220076

import os


os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

matrixA = np.array([[1,2,3],
                    [3,6,9]])

rank = np.linalg.matrix_rank(matrixA)

print(rank)

OUTPUT:

<img width="1917" height="1015" alt="Screenshot 2026-05-07 142336" src="https://github.com/user-attachments/assets/1ef9ed9a-d6c7-4028-93a5-31c6d05c5340" />



<img width="1058" height="108" alt="Screenshot 2026-05-07 142402" src="https://github.com/user-attachments/assets/260728a7-52d9-4872-8052-393c8015a251" />

Result:



Thus the rank for the given matrix is successfully solved by using a python program.



