# CSS calc() Gotchas

This repository demonstrates some uncommon errors related to the CSS `calc()` function. Specifically, it highlights unexpected behavior when combining percentages and other units, as well as the importance of correct spacing within the `calc()` expression.

## Problem 1: Percentage Calculation Order
The browser's evaluation order within `calc()` can lead to inaccurate results when percentages are combined with fixed units. The solution often requires restructuring the calculation or using alternative approaches to achieve the desired outcome.

## Problem 2: Spacing in calc()
Incorrect spacing around operators in `calc()` can result in parsing errors.  Maintaining consistent and correct spacing ensures proper calculation.