# Functioning Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

> "Complexity is anything that makes software hard to understnad or to modify."

### What is functional programming?

A programming paradigm 

- Style of Building the Structure
- Elements of computer programs
- evaluation of mathematical functions
- avoids changing-state and mutable data -["Wikipedia"](https://en.wikipedia.org/wiki/Functional_programming)

#### Pure Functions

<img src = "../images/rose.jpg" height = '300px'>

Functionial programming is pure functions.

**How do we know if a function is pure or not?**

- it returns the same result if given the same arguments (it is also referred as deterministic)
- It does not caus any observable side effects

**Reading files**

- if the function reads an external file, it's not pure function
- The external file could change

**Random number gerneration**

- Any function that relies on a random number generator cannot be pure (Salmon Cookies)

**It does not cause any observalbe side effects**

- observale side effects include modifying a global object or parameter passed by reference ( counter = 1 example - changed to a function to make it pure)

***Pure functions are stable, consistend, and predictable.***


#### Pure Funcions Benefits

- Code is definitely easier to test - unit test pure fuctions with different contexts

### Immutability

> Unchanging over time or unable to be changed

- When data is immutable, its state cannot change after it's created. If you want to change an immutable object, you can't. Instead, you create a new object with the new value.

**Mutation by doing a function composition**

- The result of a function will be used as an input for the next funciton without modifying the originla input string



### Referential transparency

**purefunctions + immutable data = referential transparency**

### Functions as first-class entities

1. refer to it from constants and variables
1. pass it as a parameter to other functions
1. return it as result from other funcitons

### Higher-order functions

1. takes one or more functions as arguments, or
1. returnes a function as it's result


- Filter
- Map
- Reduce


#### Filter

- Imperative approach
  - create a new empty array
  - iterate over the array
  - push the numbers to the empy array

- Declarative approach
  - we have a list of people
  - we have afunction
  - we filter all peple based on this function

#### Map

The map method transforms a collection by appplying a function to all of its elements and building a new collection from the returned values

***The whole idea is to transform a given array int a new array.***

#### Reduce

- filter by book type
- transform teh shopping cart into a collection of amount using map
- combine all items by adding them up with reduce



## [Refactoring JavaScript for Readability](https://dev.to/healeycodes/refactoring-javascript-for-performance-and-readability-with-examples-1hec)

#### Strategies

  1. Return early from functions
  1. Cache variables so functions can be read like sentences
  1. Check for Web APIs before implemtning your own functionality
  
