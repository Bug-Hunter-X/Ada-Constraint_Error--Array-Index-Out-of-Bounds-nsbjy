# Ada Constraint_Error: Array Index Out of Bounds

This example demonstrates a common error in Ada programming: attempting to access an array element using an index that is outside the defined bounds of the array.  This results in a `Constraint_Error` exception.

The `bug.ada` file contains code that causes this error. The `bugSolution.ada` file shows how to handle this error gracefully.

This is a good example of the importance of robust error handling in Ada.  Failing to check array bounds before access can lead to unexpected program termination.

## How to reproduce

1. Compile `bug.ada`.
2. Run the compiled executable.
3. Observe the `Constraint_Error` exception being raised.

## How to fix

The solution involves adding checks to ensure the index is within the valid range before accessing the array element.  See `bugSolution.ada` for an example of how to implement these checks.