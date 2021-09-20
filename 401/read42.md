# READING 42: Pythonisms

## Dunder (Magic, Special) Methods

- a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores,

  - Example: init or str

  - Useful, but it's recommended not to over use them.

- Object Initialization: init
- Object Representation: str, repr
- Iteration: len, getitem, reversed
- Operator Overloading for Comparing Accounts: eq, lt
- Operator Overloading for Merging Accounts: add
- Callable Python Objects: call
- Context Manager Support and the With Statement: enter, exit

## Iterators

- Iterators provide a sequence interface to Python objects that’s memory efficient and considered Pythonic. Behold the beauty of the for-in loop!
- To support iteration an object needs to implement the iterator protocol by providing the iter and next dunder methods.
- Class-based iterators are only one way to write iterable objects in Python. Also consider generators and generator expressions.

## Generators

- Generators use yield statements instead of return. Local variables and the execution state of the generator function are only stashed away temporarily and not thrown out completely. Generators start raising StopIteration exceptions after control flow leaves the generator function by any means other than a yield statement.
