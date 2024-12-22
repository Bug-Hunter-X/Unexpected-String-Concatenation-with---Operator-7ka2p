# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript bug related to type coercion and the `+` operator.  When one operand of the `+` operator is a string, JavaScript performs string concatenation instead of numerical addition. This can lead to unexpected results if not handled carefully.

## Bug
The `bug.js` file contains a function that adds two numbers. However, due to type coercion, it produces an incorrect string concatenation when one input is a string.

## Solution
The `bugSolution.js` file provides a corrected version of the function that explicitly checks for numeric inputs, preventing string concatenation.