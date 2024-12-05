# Unexpected String Concatenation in JavaScript

This example demonstrates a common error in JavaScript due to its dynamic typing. When adding a number and a string, JavaScript performs string concatenation instead of numerical addition.

## Bug

The function `foo` is expected to add two numbers. However, when passed a number and a string, it concatenates them as strings.

## Solution

The solution is to explicitly convert the input to a number before performing the addition, using `parseInt()` or `Number()`.