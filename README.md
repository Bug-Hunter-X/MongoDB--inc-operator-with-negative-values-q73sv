# MongoDB $inc operator with negative values
This repository demonstrates an uncommon bug related to the usage of the `$inc` operator in MongoDB when dealing with negative increments. The `$inc` operator is used to increment or decrement a numeric field by a specified value, but unexpected behaviors may occur if not handled correctly.

## Bug Description
The bug arises when the `$inc` operator is used with a negative value on a field that is not initialized or doesn't contain a numeric value. This can lead to errors or unexpected results. The provided code demonstrates the error, and the solution shows a robust way to handle negative increments using `$inc` with proper error handling.