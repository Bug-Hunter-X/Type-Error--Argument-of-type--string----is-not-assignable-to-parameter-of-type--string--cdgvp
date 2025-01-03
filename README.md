# TypeScript Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common TypeScript type error and its solution. The error occurs when an array of strings is passed as an argument to a function expecting a single string.

## Problem

The `greeter` function expects a single string argument (`person`) but receives an array of strings.  This results in a type error because the function cannot handle the array input.

## Solution

The solution involves modifying the `greeter` function to accept either a single string or an array of strings, and handling both cases appropriately.  This can be done using type guards or function overloading.