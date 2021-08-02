# Reading08

## List Comprehensions in Python

- List comprehension offers a shorter syntax when you want to create a new list based on the values of an existing list.

- It consists of brackets containing an expression followed by a for clause, then zero or more for or if clauses. The expressions can be anything, meaning you can put in all kinds of objects in lists.

### Syntax

The list comprehension starts with a ‘[‘ and ‘]’, square brackets, to help you remember that the result is going to be a list.

[ expression for item in list if conditional ]
is equal to
`for item in list: if conditional: expression`

## Primer on Python Decorators

### Class Objects

- In Python, functions are first-class objects. This means that functions can be passed around and used as arguments

- Inner Functions t’s possible to define functions inside other functions. Such functions are called inner functions.

- Returning Functions From Functions Python also allows you to use functions as return values. The following example returns one of the inner functions from the outer parent() function.
