# Julia Function Bug
This repository contains a simple Julia function with a bug related to handling the zero value. The bug and its solution are described below.

## Bug Description
The `myfunction` function is supposed to return the square of its input if the input is positive, and the negative of the square if the input is negative. However, it does not handle the case where the input is zero correctly.  The function should return 0 if the input is 0. 

## Bug Solution
The solution addresses the issue by adding an explicit check for the zero condition, ensuring the function returns 0 when the input is 0.

## How to reproduce
1. Clone the repository
2. Run bug.jl to see the incorrect behavior
3. Run bugSolution.jl to see the corrected function.