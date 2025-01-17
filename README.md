# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the numpy module to use the built-in functions for calculation 
### Step 2:Prepare the lists from each Rank of the matrix and assign in np.array() 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by:n. neethiventhan  
#RegisterNumber:23006643
import numpy as np
matrix = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(matrix)
print(rank)
~~~

## Output:
![image](https://github.com/Neethiventhan123/RANK-OF-A-MATRIX/assets/148514848/d985d954-567a-4d28-899a-5bf272b650f0)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

