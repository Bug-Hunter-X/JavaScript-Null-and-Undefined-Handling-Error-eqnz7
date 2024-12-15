# JavaScript Null and Undefined Handling
This repository demonstrates a common error in JavaScript related to handling null and undefined values.  The `foo` function correctly handles `null` but throws a `TypeError` when given `undefined`.  The solution shows how to improve the function to handle both cases robustly.

## Bug
The original code lacks a check for `undefined` before accessing the `length` property, which leads to an error when `undefined` is passed as an argument.

## Solution
The improved code adds a check for `undefined`, ensuring the function handles both `null` and `undefined` gracefully.