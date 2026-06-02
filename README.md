# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	(i)
	Step 1: Start the program.

Step 2: Import the NumPy library.

Step 3: Read the matrix input from the user.

Step 4: Store the matrix in a variable.

Step 5: Compute the 1-Norm of the matrix using:

∥A∥
1
	​

=
j
max
	​

i
∑
	​

∣a
ij
	​

∣

where the maximum absolute column sum is calculated.

Step 6: Use the function:

np.linalg.norm(matrix, 1)

to find the 1-Norm.

Step 7: Format the result to two decimal places.

Step 8: Display the computed 1-Norm.

Step 9: Stop the program.

(ii)
Step 1: Start the program.

Step 2: Import the NumPy library.

Step 3: Read the matrix input from the user.

Step 4: Store the matrix in a variable.

Step 5: Compute the 2-Norm of the matrix using:

∥A∥
2
	​


which is the largest singular value of the matrix.

(iii)
Step 1: Start the program.

Step 2: Import the NumPy library.

Step 3: Read the matrix input from the user.

Step 4: Store the matrix in a variable.

Step 5: Compute the Infinity Norm of the matrix using:

∥A∥
∞
	​

=
i
max
	​

j
∑
	​

∣a
ij
	​

∣

which represents the maximum absolute row sum of the matrix.


## Program:

# Register No:212225240057
# Developed By:JAYENTHAN.R
# 1-Norm of a Matrix

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))





## Output:
### 1-Norm of a Matrix
<img width="1919" height="1018" alt="Screenshot 2026-06-02 102902" src="https://github.com/user-attachments/assets/e78b4c68-2bb1-4b91-9603-80914947917b" />


### 2-Norm of a Matrix
<img width="1918" height="1015" alt="Screenshot 2026-06-02 102917" src="https://github.com/user-attachments/assets/bf37a430-c1b4-4c11-8e3a-1d75adcf1ccc" />


### Infinity Norm of a Matrix
<img width="1919" height="1025" alt="Screenshot 2026-06-02 102931" src="https://github.com/user-attachments/assets/dc671bb8-e6b7-4348-9fc5-069acff3034b" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
