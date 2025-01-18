# JavaScript Loose Comparison Pitfalls with null and undefined

This repository demonstrates a common JavaScript error related to loose comparison (==) when dealing with null and undefined values.  The loose comparison operator does not perform strict type checking, leading to unexpected type coercion and potentially incorrect results.

The `bug.js` file contains code illustrating this issue. The `bugSolution.js` file demonstrates the correct way to handle null and undefined values using the strict equality operator (===).