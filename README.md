# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The error occurs when providing a string value instead of a number for the increment.  The solution provides the correct way to use `$inc`.

## Bug
The original code incorrectly uses a string value for the increment, leading to an error. 

## Solution
The corrected code demonstrates the correct usage of `$inc` with a numerical value.