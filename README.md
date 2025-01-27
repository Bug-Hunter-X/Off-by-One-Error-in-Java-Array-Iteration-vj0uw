# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

The error arises from an incorrect loop condition in the `main` method. The loop attempts to access an index that is out of bounds for the array, resulting in an `ArrayIndexOutOfBoundsException`.

The solution involves adjusting the loop condition to ensure that the loop terminates before accessing an invalid index.