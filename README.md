# R Programming: Caching Matrix Inverse

Built as part of the **R Programming** course (programming assignment 2) in the **Johns Hopkins Data Science Specialization** (Coursera), 2024. This is a fork of rdpeng's template with completed solution.

## What's inside

- cachematrix.R: Functions for caching matrix inverse operations using R's scoping rules
  - makeCacheMatrix: Creates a special "matrix" object that stores and caches the inverse
  - cacheSolve: Computes matrix inverse, retrieving from cache if already calculated

## Notes

Solution to programming assignment 2, demonstrating use of R's `<<-` operator and lexical scoping to preserve state within function closures. Fork of rdpeng's template repository.
