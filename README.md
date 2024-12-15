# Unexpected Mutability and References in F#

This example demonstrates a potential source of confusion in F# related to mutable variables and references.  The code uses a mutable variable (`x`) and a reference (`y`) to modify its value indirectly. This behavior might not be immediately apparent to programmers accustomed to languages with different approaches to mutability.

## How to reproduce

1. Compile and run `bug.fs`.
2. Observe the output which unexpectedly shows 2 instead of 1

## Solution

Refer to the `bugSolution.fs` file for a discussion and a demonstration of how to work with mutability and references more safely, clearly, and predictably in F#.