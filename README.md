# java-concurrency

## What is concurrency?

Multiple threads of execution at the same time which results in an upredictable order of execution.

## Why use concurrency?

- Can simplify code by turning asynchronous operations into synchronous code.
- Improves application responsiveness

## Problems introduced by concurrency

1. Modifying state across threads can result in corruption
2. Locking can result in dead locks

## Problem patterns

1. Race conditons
   1. Compond actions
      1. check-then-act (example: lazy initialization)
      2. read-modify-write (example: incrementing a value)
2. Lock mismatch - same lock needed for accessing data
      
## Concept

- Atomic : An operation that is completed in one step

## Thread Safety

- Immutable data (read only data)
