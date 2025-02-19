# Next.js 15 Runtime Error: Undeclared Variable in Functional Component

This repository demonstrates a runtime error in Next.js 15 that occurs when accessing an undeclared variable within a functional component. The error isn't caught during development and only surfaces in production.

## Problem

The `pages/about.js` file attempts to access the variable `undeclaredVariable` which is not defined, leading to a runtime error. This happens because Next.js 15's strict mode catches this error only during runtime. 

## Solution

The solution involves adding proper error handling or ensuring the variable is declared and initialized before use. The `pages/aboutSolution.js` provides a corrected version with error handling.