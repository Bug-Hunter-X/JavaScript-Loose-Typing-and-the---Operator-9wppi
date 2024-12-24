# JavaScript Loose Typing and Unexpected String Concatenation

This example demonstrates a common JavaScript pitfall related to loose typing and the behavior of the `+` operator when used with numbers and strings.

## The Problem

JavaScript's dynamic typing allows for implicit type coercion. When the `+` operator encounters both a number and a string, it treats the operation as string concatenation instead of numerical addition. This can lead to unexpected results.

## Code Example

The `bug.js` file contains a simple function `foo` that adds two arguments.  However, the results are unexpected when strings are involved.

## Solution

The `bugSolution.js` file provides a solution to mitigate this issue by explicitly converting the arguments to numbers before performing the addition. 

## How to Run

1. Save the code snippets as `bug.js` and `bugSolution.js`.
2. Run the files using a JavaScript interpreter (Node.js, browser's console, etc.).