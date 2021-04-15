# JS Debugging

## Error Handling and Debugging

### Order of execution

- When there are errors it can be due to where in the sequence of functions and when it happens.  A specific function may not run if another function is not called first. 

- Execution Context - This is a context that is broken down into three
1. Global context
2. Function context
3. Eval context

- Variable Scope - This si broken down into two
1. Global Scope
2. Function Level Scope

**When script enters a new execuption context, the are two phases of activity**

The first phase is the prepare phase.  This is where a new scope is executed then varibables, functions and arguments are created.  The second step is Execute. This is where a value is assigned to a variable, where functions are referenced and run and statements are executed.

When an erro is found it will have different compnents.
1. Name, this gives you the type of error it is.
2. Message, This is a description of the error.
3. File Number, This gives you the file that is being referenced.
4. Line number, Tell you which line in the code is giving you the error.

### Different kinds of errors that can be seen

1. SytaxError
2. ReferenceError
3. EvalError
4. URIError
5. TypeError
6. Error
7. RangeError
8. NaN

### Debugging workflow

- Where is the problem?
1.Find the script where the problem is occuring
2.Find the line number
3.What is the type of error

- What is the problem?
1.Can you spot the error in the variables
2.Break it down into smaller pieces
3.Check numbers or parameters and items in an array.
