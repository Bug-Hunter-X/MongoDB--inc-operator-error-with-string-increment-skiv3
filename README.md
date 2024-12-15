# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error arises from providing a string value to the `$inc` operator, which expects a number. The solution shows the correct way to use the operator with numerical increments.

## Bug

The `bug.js` file contains the incorrect code that uses a string value instead of a number for incrementing.

## Solution

The `bugSolution.js` file contains the corrected code that uses a number value for incrementing the field in MongoDB using the `$inc` operator. 
