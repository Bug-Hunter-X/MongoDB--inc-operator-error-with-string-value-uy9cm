# MongoDB $inc operator error with string value
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB, leading to an error. The `$inc` operator is used to increment or decrement a numeric field in a document. Attempting to increment with a non-numeric value will throw an error. 

The solution shows how to fix the issue by passing a numerical value to the `$inc` operator.

## Bug
The original code attempts to increment the `count` field by the string value 'abc', which is invalid. This results in a MongoDB error indicating that the value cannot be incremented. 

## Solution
The solution replaces the string value 'abc' with the numerical value 1, ensuring the `$inc` operator functions correctly.
