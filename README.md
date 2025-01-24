# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error occurs due to an incorrect loop condition, leading to an `ArrayIndexOutOfBoundsException`. The solution shows how to correct the loop condition to avoid this error.

## Bug Description
The provided Java code calculates the sum of elements in an integer array.  However, due to an error in the loop condition, it attempts to access an index beyond the bounds of the array, resulting in an `ArrayIndexOutOfBoundsException`.

## Solution
The solution corrects the loop condition to iterate up to, but not including, the array's length. This prevents accessing an index outside the array's valid range.