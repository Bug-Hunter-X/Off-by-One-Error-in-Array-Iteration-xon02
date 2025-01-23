# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The `BuggyArraySum.java` file contains a for loop that attempts to access an array element beyond its bounds, leading to an `ArrayIndexOutOfBoundsException`.  The corrected version, `CorrectedArraySum.java`, shows how to fix this error.

**Key Learning:** Pay close attention to loop termination conditions when working with arrays in Java. Remember that arrays are zero-indexed, and the last valid index is `arr.length - 1`.