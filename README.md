# Haskell Infinite Recursion Bug

This repository demonstrates a common error in Haskell programming involving infinite recursion caused by attempting to pattern match on an infinite list. The code in `bug.hs` attempts to sum the elements of an infinite list, resulting in a stack overflow.  The solution, in `bugSolution.hs`, showcases a safe and efficient way to handle such scenarios.