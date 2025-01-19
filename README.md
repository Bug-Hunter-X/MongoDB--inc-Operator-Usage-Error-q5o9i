# MongoDB $inc Operator Usage Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.
The error occurs when attempting to increment a numeric field with a non-numeric value.  This example showcases the incorrect usage and provides a corrected solution.
## Problem
The provided JavaScript code attempts to increment the `myField` field of a document in the `myCollection` collection.  However, it provides a string value ("1") to the `$inc` operator instead of a number. This causes unexpected behavior and potentially a failure of the update operation.
## Solution
The solution involves correctly providing a numeric value to the `$inc` operator to achieve the intended behavior of incrementing the numeric field.
