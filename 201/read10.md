# Read 10

## Error Handling & Debugging
* If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
* To find the source of an error, it helps to know how scripts are processed.
* The JavaScript interpreter uses the concept of execution contexts.
* **EXECUTION CONTEXT**  JavaScript Hello Molly Every statement in a script lives in one of three execution contexts: GLOBAL CONTEXT, FUNCTION CONTEXT, EVAL CONTEXT (NOT SHOWN).
* EXECUTION CONTEXT & HOISTING: Each time a script enters a new execution context, there are two phases
of activity:
  - PREPARE
  - EXECUTE
* If a JavaScript statement generates an error, then it throws an exception.
* Error objects can help you find where your mistakes are and browsers have tools to help you read them.
* Debugging is the process of finding errors. It involves a process of deduction.
* The console helps narrow down the area in which the error is located, so you can try to find the exact error.
* JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. 
