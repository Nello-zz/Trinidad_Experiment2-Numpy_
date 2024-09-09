# EXPERIMENT 2: NUMERICAL PYTHON (NUMPY)

In this experiment, we are tasked with the following objectives:
- Identify the functions and features available in the Numpy library.
- Apply and utilize various Numpy functions in Python to solve problems.

We are given two problems to solve, and Jupyter Notebook will be used to write the code.

### Problem 1: Normalization

### Instructions:
Create a random 5x5 ndarray and store it in the variable `X`.
Normalize `X` using the z-score formula: 

𝑍 = (𝑋 − 𝑥̅) / σ


  Here, x̄ is the mean and σ is the standard deviation. In Python, you can calculate the mean and standard deviation element-wise using the `.mean()` and `.std()` functions, respectively.
  
- Save your normalized ndarray as `X_normalized.npy`.

### Problem 2: Divisible by 3

### Instructions:
Create a 10x10 ndarray containing the squares of the first 100 positive integers.
Example:




    𝐴 = [  1     4     ⋯   81    100 
            ⋮      ⋮     ⋱     ⋮     ⋮
            ⋮      ⋱     ⋮     ⋮     ⋮
            ⋮      ⋮     ⋱     ⋮     ⋮    
          8281  8464   ⋯   9801 10000]
 

From this array, find all the elements that are divisible by 3.
Save the result as `div_by_3.npy`.


