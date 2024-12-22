# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common bug in Java: an `ArrayIndexOutOfBoundsException`. The code iterates through an array using a for loop with an incorrect condition, leading to an attempt to access an element beyond the array's bounds. The solution shows how to fix the code by adjusting the loop condition.

## Bug Description

The provided Java program creates an integer array of size 5 and tries to populate it with even numbers. The for loop's condition `i <= array.length` is wrong.  It should be `i < array.length` to prevent accessing the element at index 5, which is out of bounds. This results in an `ArrayIndexOutOfBoundsException`.

## Solution

The solution corrects the loop condition to `i < array.length`. This ensures that the loop iterates only up to the last valid index of the array.