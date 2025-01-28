# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` caused by division by zero.  The `bug.java` file contains the erroneous code, while `bugSolution.java` provides a corrected version that handles potential division by zero.

## Bug Description

The bug arises from attempting to divide an integer by zero, a mathematically undefined operation. Java throws an `ArithmeticException` in such cases to signal an error.

## Solution

The solution involves checking if the divisor is zero before performing the division. If the divisor is zero, an appropriate action can be taken, such as printing an error message, returning a default value, or throwing a custom exception.