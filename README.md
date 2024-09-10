# Programming-Assignment-2

## Normalization Problem
Function Used:
  - import numpy as np
  - np.random.rand()
  - np.save()
  - mean()
  - std()
  - print()

Documentation:
- ###Importing numpy:

Initially import the numpy library using import numpy as np to access numpy functions.

###- Generating a random array:

Create a 5x5 array of random numbers using X = np.random.rand(5, 5).

###- Calculating statistics:

Calculated the mean of the array using X_mean = X.mean().

Calculated the standard deviation of the array using X_std = X.std().

###- Normalizing the array:

Normalized the array with the formula: X_normalized = (X - X_mean) / X_std.

###- Saving the normalized array:

Saved the normalized array to a .npy file using np.save('X_normalized.npy', X_normalized).

###- Previewing the result:

Printed the normalized values using print(X_normalized) to check the output.

## Divisible by 3 Problem
Function Used:
  - import numpy as np
  - np.arange()
  - np.reshape()
  - np.save()
  - print()

In this problem, just like the previous problem i started with importing numpy as np to use the functions of numpy.

Updates:
1: Initial Post
2: Upload npy files
3: Added ReadMe
4: 
