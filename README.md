# Unexpected Error in MATLAB Function with Empty Input

This repository demonstrates an uncommon error in MATLAB that occurs when a function receives an empty input array. The error message is not very informative, making debugging difficult.  The solution shows how to handle empty inputs gracefully.

## Bug
The `myFunction.m` file contains a function that produces an unexpected error when it's passed an empty array. The error is not explicitly related to empty arrays, making it harder to identify.

## Solution
The `bugSolution.m` file provides a corrected version of the function. It explicitly checks for empty inputs and handles them appropriately, preventing the unexpected error.