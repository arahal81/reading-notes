# reading 09

## Functional Programming Concepts

1. What is functional programming?
    * is a way of thinking about software construction by creating pure functions. It avoid concepts of shared state, mutable data observed in Object
     Oriented Programming.
2. What is a pure function and how do we know if something is a pure function?
    * The Pure function always returns the same result if the same arguments are passed in.
      It does not depend on any state, or data, change during a program’s execution. It must only depend on its input arguments.
3. What are the benefits of a pure function?
    * It easier to reason about

    * It easier to combine

    * It easier to test

    * It easier to debug

    * It easier to parallelize

4. What is immutability?
    * Immutability means unchangeable. It is the divine attribute of unchangeableness.

5. What is Referential transparency?
    * if a function consistently yields the same result for the same input, it is referentially transparent.

## Modules and require

1. What is a module?
    * a set of related functions and components semantically related with its own functional responsibility.  
2. What does the word ‘require’ do?
    * require function is intended to add separate pieces of code (“modules”) to the current scope,
