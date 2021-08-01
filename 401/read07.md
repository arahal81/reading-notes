# Reading07

## Python scope

The scope of a variable or name defines its visibility throughout your code. In Python, scope is implemented as either a Local,
Enclosing, Global, or Built-in scope. When you use a variable or name, Python searches these scopes sequentially to resolve it.

If the name isn’t found, then you’ll get an error. This is the general mechanism that Python uses for name resolution and is known as the LEGB rule.

## The nonlocal Statement

With a nonlocal statement, you can define a list of names that are going to be treated as nonlocal.
nonlocal names can be accessed from inner functions, but not assigned or updated.

Take advantage of Python scope to avoid or minimize bugs related to name collision

Make good use of global and local names across your programs to improve code maintainability

Use a coherent strategy to access, modify, or update names across all your Python code Additionally,

you’ve covered some scope-related tools and techniques that Python offers and how you can use them to gather information

about the names that live in a given scope or to modify the standard behavior of Python scope.

Of course, there’s more to this topic that’s outside the scope of this tutorial,

so get out there and continue to tackle name resolution in Python.
