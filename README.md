# Unexpected Behavior of `calc()` in CSS due to Spaces

This repository demonstrates an uncommon bug in CSS related to the use of spaces within the `calc()` function.  Incorrect spacing around operators in `calc()` can lead to unexpected results.

## Bug Description:
Spaces around the operators (+, -, *, /) in CSS `calc()` function can break the calculation. The correct syntax requires no spaces around the operators.

## How to Reproduce:
1. Clone this repository.
2. Open `bug.css` and `bugSolution.css` to see the buggy and corrected code respectively.
3. Observe the differences in the rendered output. 

## Solution:
Ensure there are no spaces around the operators in the `calc()` function.  The correct format should be `calc(100% - 20px)`, not `calc(100% - 20 px)`. 