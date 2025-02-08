# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common error in JavaScript and how to handle it effectively. The error occurs when attempting to access the 'length' property of a variable that holds an undefined value.

## Bug Description

The provided JavaScript code defines a function `foo` that aims to return the length of an array. It correctly handles the case where the input `x` is `null`. However, if the input is `undefined`, it throws a `TypeError` because you cannot access the 'length' property of an undefined value.

## Solution

The solution involves adding a check for `undefined` before accessing the 'length' property.  This prevents the error from occurring, and the improved function gracefully handles both `null` and `undefined` inputs by returning 0.

## How to Run

1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code.
4. Run the JavaScript files in a Node.js environment or a web browser's console.