# JavaScript Division by Zero Error

This repository demonstrates a common error in JavaScript: division by zero.  The `myFunc` function attempts to divide `a` by `b`, but does not handle the case where `b` is zero.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file demonstrates the corrected code with proper error handling.

## Bug:
The original code throws an error when the divisor is zero. This is because division by zero is undefined in mathematics and causes an error in most programming languages.

## Solution:
The solution file adds a check to see if the divisor is zero.  If it is, the function returns a specific value (e.g., Infinity, NaN, or an error message) or handles the error in a more graceful manner, preventing the program from crashing.