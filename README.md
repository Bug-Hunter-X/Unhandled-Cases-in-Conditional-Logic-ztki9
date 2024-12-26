# Unhandled Cases in Conditional Logic
This repository demonstrates a common JavaScript bug related to unhandled cases in conditional logic.  The provided code snippet uses `if` statements to check for specific values of `x`, but fails to provide a default behavior if `x` does not match either of those values. This can lead to unexpected behavior or runtime errors. The solution adds a default `else` clause to handle cases where `x` is neither 1 nor 2.

## Bug
The original code lacks comprehensive handling of all possible input values. This makes the function's behavior unpredictable for inputs outside the explicitly checked values.

## Solution
The solution includes a default `else` statement to provide consistent behavior when `x` is neither 1 nor 2, returning `null` in this case.  This makes the function's behavior more predictable and robust.