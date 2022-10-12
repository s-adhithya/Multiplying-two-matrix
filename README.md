# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.
## ALGORITHM:
### Step 1:
 Import numpy as np
### Step 2:
 Create an empty list
### Step 3:
Use append of the two lists
### Step 4:
Assign the arrays
### Step 5:
In result multiply the assigned variables
### Step 6:
Run the program
## PROGRAM: 
```python
To write a python program for multiplying two matrix.
Developed by: Adhithya.S
Reference no: 22005823
import numpy as np
l1, l2 = [],[]
n= int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1= np.array(l1)
value2 = np.array(l2)
result = value1*value2
print("Product of two arrays is:",result)
```
## OUTPUT:
![output](/filename2.png)
## RESULT:
Thus the program is written to multiply two matrix.
