# Programming-Assignment-2

## Normalization Problem
#### Function Used:
  - import numpy as np
  - np.random.rand()
  - np.save()
  - mean()
  - std()
  - print()

#### Documentation:
a. Importing numpy:

- Initially import the numpy library using import numpy as np to access numpy functions.

b. Generating a random array:

- Create a 5x5 array of random numbers using X = np.random.rand(5, 5).

c. Calculating statistics:

- Calculated the mean of the array using X_mean = X.mean().

- Calculated the standard deviation of the array using X_std = X.std().

d. Normalizing the array:

- Normalized the array with the formula: X_normalized = (X - X_mean) / X_std.

e. Saving the normalized array:

- Saved the normalized array to a .npy file using np.save('X_normalized.npy', X_normalized).

f. Previewing the result:

- Printed the normalized values using print(X_normalized) to check the output.

## Divisible by 3 Problem
#### Function Used:
  - import numpy as np
  - np.arange()
  - np.reshape()
  - np.save()
  - print()

#### Documentation:
a. Importing numpy:

- Initially import the numpy library using import numpy as np to access numpy functions.

b. Genrate the array

- Creat a 10x10 array of consecutive integers starting from 0 using A = np.arange(1, 101).reshape(10, 10).
Exponentiated each value in the array by 2 using A = A**2.

c. Finding values divisible by 3:

- Identified the values divisible by 3 using div_by_3 = A[A % 3 == 0].

d. Saving the result:

- Saved the div_by_3 array to a .npy file using np.save('div_by_3.npy', div_by_3).

e. Previewing the arrays:

- Print the original array and the div_by_3 array using print(A) and print(div_by_3) to check the values.

## Updates:
1 - Initial Post
2 - Upload NPY files
3 - Added ReadMe
4 -  
