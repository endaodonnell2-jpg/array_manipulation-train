NumPy Array Manipulation and Linear Algebra Examples
Overview
This project demonstrates fundamental NumPy operations and linear algebra concepts through practical examples. It covers:

Creating and reshaping multi-dimensional arrays

Accessing and modifying elements within arrays

Generating arrays of zeros, ones, and constant values

Performing arithmetic operations and element-wise calculations

Matrix multiplication, calculating determinants, and matrix inverses

Statistical summaries such as minimum, maximum, and sum values (overall and along specific axes)

Reshaping and stacking arrays both vertically and horizontally

These examples help build a strong foundation for data manipulation and linear algebra tasks in Python using NumPy.

Key Features Explained
Multi-dimensional Arrays:
Create a 3D NumPy array containing integers from 1 to 12, reshaped into shape (2, 2, 3). Extract specific elements by indexing into layers, rows, and columns. You can also retrieve entire slices such as the first layer or a particular column across all layers.

Modifying Arrays:
Replace an entire row in a given layer with a constant value (e.g., replacing the second row in the first layer with 99).

Arrays of Zeros, Ones, and Constants:
Generate arrays filled with zeros, ones, or any constant value with specified shapes and data types.

Arithmetic Operations:
Perform element-wise addition and multiplication. For example, add an array of fives to an array of zeros or multiply an array of ones by 10. Calculate powers element-wise (e.g., square all elements of an array).

Matrix Operations:
Multiply two compatible matrices using np.matmul(). Calculate the determinant and inverse of a 2x2 matrix using functions from np.linalg.

Statistical Summaries:
Compute the minimum, maximum, and sum of values in a 2D array overall. Also calculate these statistics along columns and rows using the axis parameter.

Reshaping Arrays:
Change the shape of a 1D array into various 2D configurations such as (2, 4), (4, 2), and (8, 1).

Stacking Arrays:
Vertically stack vectors to create multi-row arrays, or horizontally stack them to create wider arrays. Demonstrates combining arrays multiple times.

How to Run
Make sure you have Python 3.6 or higher installed.

Install NumPy if you don’t have it yet, by running:
pip install numpy
python your_script_name.py

Sample Output Highlights
The printed 3D array displays integers 1 through 12 arranged in two layers.

Confirmation of the number of array dimensions.

Extracted elements such as the value at layer 1, row 0, column 2.

The entire first layer and the entire third column across all layers.

Modified array where the second row of the first layer is replaced with 99s.

Arrays of zeros, ones, and constant sevens with specified shapes.

Results of adding arrays, multiplying by scalars, and element-wise squaring.

Matrix multiplication producing a 2x2 result.

Determinant and inverse of a 2x2 matrix.

Minimum, maximum, and sum statistics for a 2D array overall and by axis.

Demonstration of reshaping arrays into different shapes.

Vertical and horizontal stacking of vectors with resulting shapes shown.


This code is an excellent introduction to core NumPy features essential for scientific 
computing, data analysis, and machine learning projects. 
The operations shown here form the building blocks for more complex array manipulations 
and linear algebra calculations.
