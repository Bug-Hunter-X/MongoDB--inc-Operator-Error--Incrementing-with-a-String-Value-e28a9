# MongoDB $inc Operator Error: Incrementing with a String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numeric field by a specified value.  However, an error occurs if you attempt to increment the field using a string value.

**Bug:** The provided `bug.js` file shows an incorrect use of the `$inc` operator where a string ('1') is passed as the increment value instead of a number (1).

**Solution:** The `bugSolution.js` file provides the corrected implementation, using a numeric value for the increment.