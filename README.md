# TypeScript Array to String Argument Error

This repository demonstrates a common TypeScript error: passing an array of strings to a function expecting a single string.  The `bug.ts` file shows the error, and `bugSolution.ts` provides a solution.

## Problem

The `greeter` function expects a single string argument.  However, the `user` variable is an array of strings.  Attempting to pass `user` to `greeter` results in a type error.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings or modifying the way the `user` variable is used.  The `bugSolution.ts` file provides an example of modifying the `greeter` function to handle the array of strings.