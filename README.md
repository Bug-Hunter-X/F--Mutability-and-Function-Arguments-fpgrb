# F# Mutability and Function Arguments

This example demonstrates a common misconception regarding mutability and function arguments in F#. When passing mutable variables to a function, the function operates on copies of the variable's value, not direct references.  Therefore, changes made to the mutable variable *after* the function call do not affect the function's results. 

The `bug.fs` file shows the initial flawed code, and `bugSolution.fs` provides a corrected version.