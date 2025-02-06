# Null Value Handling in JavaScript

This repository demonstrates a common JavaScript bug related to handling null values and provides a solution.

## Bug Description

The original JavaScript function `foo` does not explicitly handle cases where the input parameters `a` or `b` might be `null`.  If `null` values are passed, this could lead to unexpected behavior or runtime errors.

## Solution

The improved function now includes a check to handle `null` values. If either `a` or `b` is `null`, the function returns 0. This prevents errors and ensures the function behaves as expected in all cases.

## How to Run

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` to see the original buggy code and the solution.
3. You can test both functions by calling them with different inputs, including null values.