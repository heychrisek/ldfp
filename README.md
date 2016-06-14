(in-progress...)

###LDFP###

Library-Driven Functional Programming. Yes, the name is tongue-in-cheek. Code should be as library-driven as it is StackOverflow-driven (that is, not very). But _learning_ can be library-driven. This repo is a curriculum of sorts, a practical introduction to Functional Programming (FP) from a JavaScript perspective, providing examples of core FP concepts through examples from open-source libraries.

The obstacle to learning FP is not lack of resources, it's being overwhelmed with resources. These examples narrow the focus to specific areas of FP by (1) identifying the FP concept itself, (2) demonstrating the "problem" it solves, and (3) providing examples of the FP solution using a JS library. The intent is to have a general notion of what FP means, but to solidify an understanding of FP by understanding the libraries herein and the problems they solve.

##Functional Programming##

> Functional Programming is when functions, not objects or procedures, are used as the fundamental building blocks of a program.
> Functional Programming is not about mathematics but about abstraction and reducing complexity.
> - ["Functional Programming"](http://c2.com/cgi/wiki?FunctionalProgramming)

That's a nice definition. Here's some of the concepts that go into FP:

 - First Class Functions
 - Higher Order Functions
 - Immutability
 - Pure functions (no side effects)
 
 - Lambda Calculus
 - Monads
 - Lexical Closures
 - Pattern Matching
 - Single Assignment
 - Lazy Evaluation
 - Garbage Collection
 - Type Inference
 - Tail Call Optimization
 - List Comprehensions

The following libraries demonstrate what these concepts are and how they can be used.

##Ramda##

[Ramda](https://github.com/ramda/ramda) is "a practical functional library for Javascript programmers."

"Functional programming is in good part about immutable objects and side-effect free functions. While Ramda does not enforce this, it enables such style to be as frictionless as possible."

 - First Class Functions
 - Higher Order Functions
 - Immutability
 - Pure functions (no side effects)

##Immutable JS##

[Immutable.js](https://github.com/facebook/immutable-js/) "provides many Persistent Immutable data structures."

 - Immutability
 - Pure functions (no side effects)

##React.js##

[React](https://github.com/facebook/react) is "a declarative, efficient, and flexible JavaScript library for building user interfaces." Without getting into the details of React, consider [the UI as a function of data](http://tylermcginnis.com/building-user-interfaces-with-pure-functions-and-function-composition-in-react-js/).

 - Data pipeline
 - Pure functions (no side effects)
 - Pure functions