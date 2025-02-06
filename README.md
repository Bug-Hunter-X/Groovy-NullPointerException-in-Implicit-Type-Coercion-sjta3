# Groovy NullPointerException in Implicit Type Coercion

This repository demonstrates a common issue in Groovy related to implicit type coercion and null values.  Groovy's flexible typing system, while convenient, can lead to unexpected null pointer exceptions if not handled correctly. 

The `bug.groovy` file shows the problematic code, while `bugSolution.groovy` provides a solution.

## How to Reproduce

1. Clone the repository.
2. Run `groovy bug.groovy` to see the unexpected behavior. 
3. Run `groovy bugSolution.groovy` to see the corrected version.

## Solution

The solution involves explicit null checks before attempting operations on potentially null values.