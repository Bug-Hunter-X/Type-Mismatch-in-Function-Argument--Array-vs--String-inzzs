# Type Mismatch in Function Argument: Array vs. String

This code snippet demonstrates a type mismatch error in TypeScript that can easily be overlooked. The `greeter` function expects a string argument, but it's called with an array of strings.  This results in a runtime error rather than a compile-time error because TypeScript's type checking doesn't always catch this kind of mismatch when arrays are involved.

The `bug.ts` file contains the buggy code.  The `bugSolution.ts` file shows how to fix the issue, either by changing the function's type signature or by iterating through the array.

This example highlights the importance of thorough testing and careful consideration of array vs. individual element types in your TypeScript functions.