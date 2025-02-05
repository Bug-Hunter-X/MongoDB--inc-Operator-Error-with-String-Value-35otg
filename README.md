# MongoDB $inc Operator Error with String Value

This example demonstrates an error that can occur when using the `$inc` operator in MongoDB with an incorrect data type. The `$inc` operator is used to increment a numerical field by a specified value.  However, if you attempt to increment with a string value, you'll encounter an error.  The solution shows the correct way to use `$inc`.

## Bug
The bug is in the use of the `$inc` operator.  The code attempts to increment the `age` field by '1', which is a string, instead of 1, which is a number.  This will result in an error.

## Solution
The solution is to ensure the increment value is a number.  The corrected code uses the number 1 instead of the string '1'.