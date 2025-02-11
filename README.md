# Go Array Index Out of Bounds

This repository demonstrates a common error in Go: accessing an array index beyond its defined bounds.

## The Bug

The `bug.go` file contains code that attempts to write values to an array with a size of 5, but the loop iterates up to index 10. This results in a runtime panic because the code tries to access memory outside the array's allocated space.

## The Solution

The `bugSolution.go` file provides a corrected version. The loop is modified to iterate only within the bounds of the array, preventing the index out of bounds error.