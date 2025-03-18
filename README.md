# Linear-Algebra - Matrix-operations
## This task involves using NumPy for matrix multiplication, generating cyclic patterns, and creating matrices framed with ones. It includes summing values across rows and columns, logical AND/OR operations, finding non-zero elements, and working with random values in an 8x8 array. It also covers creating custom n×n matrices based on specific rules.
### Assignment from SGH
Task:
Use NumPy to perform the following tasks:

Compute the multiplication of the following matrices:
[[1, 0], [0, 1]]

[[1, 2], [3, 4]]

Generate an array of length 3n filled with the cyclic pattern 1, 2, 3.

Create a 10×10 matrix of zeros and then "frame" it with a border of ones.

Create a random 3×5 array using the np.random.rand(3, 5) function and compute: the sum of all the entries, the sum of the rows and the sum of the columns. (many Numpy functions have an optional axis= argument!)

Given the following arrays representing logical values (0 = False, 1 = True) compute the logical AND and logical OR operations for every pair of values of the two arrays: [1, 1, 0, 0] [1, 0, 1, 0] Hint: you may need to set the data type (dtype) of the array's elements to 'bool'

Find indices of non-zero elements from [1, 2, 0, 0, 4, 0]

Create a 8×8 array with random values and find minimum and maximum value

Create a 8×8 array with random natural values from the range (1-100) on the diagonal, other values should be 0. Hint: You can use numpy's 'eye' function.

Write a function which creates an n×n matrix with (i,j)-entry equal to i+j.

Write a function which creates an n×n matrix with rows having subsequent values multiplied by the row's number. For example for n = 4:

[[0, 1, 2, 3], [0, 2, 4, 6], [0, 3, 6, 9], [0, 4, 8, 12]]
