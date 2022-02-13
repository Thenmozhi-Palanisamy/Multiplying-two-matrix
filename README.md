# Multiplying-two-matrix

## AIM:
To find the Multiplying -two-matrix
## ALGORITHM:

### Step 1:
Start the program.
### Step 2:
Enter the row and column of the first matrix.
### Step 3:
Enter the row and column of second matrix.
### Step 4:
enter the elements of the first matrix.
### Step 5:
Enter the elements of second matrix.

## PROGRAM:
import numpy as np
n = int(input())
m1,m2=[],[]
for i in range(n):
    m1.append(int(input()))
for i in range(n):
    m2.append(int(input()))
A = np.array(m1)
B = np.array(m2)
result = A*B
print("Product of two arrays is:",result) 

## OUTPUT:
![output](.//multiply.png)

## RESULT:
Thus the multiplying-two-matrix is implemented using the python programming

