# Reading03

## Read & Write Files in Python

- Files at their core are a bytes of data binary of 0s and 1s in order to make the computer understand them, files generally contain of 3 parts:
  - Header: metadata about the contents of the file (file name, size, type, and so on)
  - Data: contents of the file as written by the creator or editor
  - End of file (EOF): special character that indicates the end of the file
- for files, paths are required to be accessed. a path is the file location. paths are consits of:
  - folder path
  - file name
  - extension

## Exceptions in Python

- An Exception is an error that occurred during the execution of a piece of code. A runtime error is called an Exception, the cause of the exception is improper
  input.
- Raising an Exception: We can use raise to throw an exception if a condition occurs. The statement can be complemented with a custom exception.

  - SyntaxError: It occurs when a syntax error is raised.

  - AsserationError: It occurs when an assert statement fails.

- The exception is handled by try, except and finally.
  - try – It checks the error in the block of code
  - except – It handles the error
  - finally – It executes the code.
