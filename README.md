# Stack Overflow Bug in Hack

This repository demonstrates a common error in recursive functions written in Hack: stack overflow.  The `foo` function calculates the factorial, but without proper handling of large inputs, it leads to exceeding the call stack limit.

The `bug.hack` file contains the buggy code.  `bugSolution.hack` provides a corrected version that addresses the stack overflow issue by introducing iteration instead of recursion.