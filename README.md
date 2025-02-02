# MongoDB $inc operator error: using string instead of number
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.

The error occurs when a string is provided as the increment value instead of a number. This results in an error because the `$inc` operator expects a numerical value.

## Bug
The `bug.js` file shows an incorrect update operation that causes an error.

## Solution
The `bugSolution.js` file demonstrates the correct way to use the `$inc` operator.

## How to reproduce the bug
1. Clone this repository
2. Make sure you have MongoDB installed and running
3. Replace `<your_database>` and `<your_collection>` with your actual database and collection names
4. Run `node bug.js`
5. Observe the error

## How to fix the bug
1. Modify the update operation in `bug.js` using the correct solution provided in `bugSolution.js`
2. Run `node bugSolution.js`
3. Verify that the update operation is successful.