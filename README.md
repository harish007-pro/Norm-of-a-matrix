# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
	# Register No: 24006523
	# Developed By: Harish G

	# 1-Norm of a Matrix
	import numpy as np
	mat=eval(input())
	ones=np. linalg.norm(mat,1)
	print(ones)

	# 2-Norm of a Matrix
	import numpy as np
	mat=eval (input ())
	twes=np. linalg.norm(mat, 2)
	print(f"{twes:.2f}")

	# Infinity Norm of a Matrix
	import numpy as np
	mat=eval(input())
	inf=np.linalg.norm(mat,np.inf)
	print(f"{inf:.2f}")
## Output:
### 1-Norm of a Matrix
![result](<Screenshot 2024-12-10 152247.png>)
### 2-Norm of a Matrix
![result](<Screenshot 2024-12-10 152306.png>)
### Infinity Norm of a Matrix
![result](<Screenshot 2024-12-10 152317.png>)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
