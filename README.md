# Unexpected Null Behavior with Strict Equality in JavaScript

This repository demonstrates a subtle but common error in JavaScript when handling null values with strict equality (===). The provided code snippet showcases a function that returns null if either of its arguments is null, even if a valid arithmetic operation would be possible.

The solution demonstrates a more robust approach for null checks, enabling the function to handle null values more gracefully and avoid unexpected null returns when only one argument is null.