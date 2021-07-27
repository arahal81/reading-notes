# Reading04

## Objects and Classes

- Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.
  Example:
  class MyClass:
  `variable = "blah" def function(self): print("This is a message inside the class.")`

we can access object variables, by declaring a variable that stores MyClass function then we call that variable then the variable we want but preceded by a dot so the code will look like the following:

`class MyClass:
variable = "blah"

    def function(self):
        print("This is a message inside the class.")

myobjectx = MyClass()
myobjectx.variable`

## Thinking Recursively in Python

- A recursive function is a function defined in terms of itself via self-referential expressions. This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share a common structure made up of two parts: base case and recursive case.
- recursive function structure is:
  - base case
  - recursive case

## Pytest Fixtures and Coverage

### Fixtures

- Fixtures: When you're writing tests, you're rarely going to write just one or two. Rather, you're going to write an entire "test suite", with each test aiming to check a different path through your code.

- fixtures can be invoked without parenthesis or calling, it invokes itself once with each test, and if we want them to be invoked more we can add a scope.

### Coverage

- Coverage: This is all great, but if you've ever done any testing, you know there's always the question of how thoroughly you have tested your code. After all, let's say you've written five functions, and that you've written tests for all of them
