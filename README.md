# TypeScript Type Mismatch Bug

This repository demonstrates a common TypeScript error: type mismatches. The `add` function is defined to accept two numbers, but a string is passed as an argument, resulting in a compile-time error.

## Bug Description

The `add` function in `bug.ts` is designed to add two numbers. However, the provided example attempts to add a number and a string, leading to a type error caught by the TypeScript compiler. This highlights the strength of TypeScript's type system in catching potential errors before runtime.

## Solution

The `bugSolution.ts` file demonstrates a corrected version, ensuring that both arguments are numbers.