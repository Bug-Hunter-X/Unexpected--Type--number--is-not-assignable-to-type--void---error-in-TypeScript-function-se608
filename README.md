# Unexpected 'Type 'number' is not assignable to type 'void'' error in TypeScript function

This repository demonstrates a common TypeScript error related to function return types.  The `printNumbers2` function is declared to return `void`, meaning it shouldn't return any value. However, an explicit `return 1;` statement causes a type error because a number is being returned where void is expected.

The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides the corrected version.

This example highlights the importance of carefully specifying and adhering to function return types in TypeScript to prevent unexpected errors during compilation.