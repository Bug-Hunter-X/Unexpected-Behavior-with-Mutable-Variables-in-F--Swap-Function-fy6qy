# F# Mutable Variable Swap Bug

This repository demonstrates a common error in F# involving the unexpected behavior of mutable variables when passed to functions.  In F#, mutable variables are passed by sharing, meaning changes within a function affect the original variables.  This can lead to unexpected results, particularly when attempting operations like swapping values.

The `bug.fs` file contains code that attempts to swap two mutable variables.  The `bugSolution.fs` file provides a corrected version using techniques to avoid this issue.