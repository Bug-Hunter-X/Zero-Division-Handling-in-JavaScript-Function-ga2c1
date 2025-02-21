# Zero Division Handling in JavaScript Function

This repository demonstrates a common error in JavaScript: incorrect handling of zero values in division.  The `bug.js` file contains a function that produces incorrect results or throws an error when either input is zero.  The `bugSolution.js` file provides the corrected version. 

## Bug Description
The `myFunction` function in `bug.js` does not correctly handle cases where the numerator or denominator is zero. This results in either an incorrect result or a runtime error (division by zero).

## Solution
The `bugSolution.js` file fixes this issue by explicitly checking for zero values before performing the division.  The corrected function handles these cases gracefully and prevents any errors.