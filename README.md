# Off-by-One Error in C Array Access
This repository demonstrates a common off-by-one error in C when accessing array elements.  The `bug.c` file contains the erroneous code, while `bugSolution.c` provides the corrected version.

The bug stems from an incorrect loop condition in the `for` loop that attempts to access an array element beyond its valid index range.  This can lead to unexpected program behavior, crashes, or security vulnerabilities.

The solution highlights the importance of carefully checking loop bounds when working with arrays in C to prevent such errors.