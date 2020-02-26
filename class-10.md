# Error Handling & Debugging

## ORDER OF EXECUTION 

**To find the source of an error, it helps to know how scripts are processed.** 

# EXECUTION CONTEXTS 

**The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.**

*Every statement in a script lives in one of three execution contexts:*

* GLOBAL CONTEXT 

* FUNCTION CONTEXT 

* EVAL CONTEXT (NOT SHOWN)

### VARIABLE SCOPE 

 * GLOBAL SCOPE 

 * FUNCTION-LEVEL SCOPE 

 **THE STACK**

 **the javascript interpreter processes one line of code at atime.**

 *When astatement needs data from another function it stacks the new function on top of the current task.*

 **EXECUTION CONTEXT & HOISTING**

 **Each time a script enters a new execution context, there are two phases of activity:**

 1: PREPARE 
 2: EXECUTE 

 **UNDERSTANDING SCOPE**

  *In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object*

  **UNDERSTANDING ERRORS** 

  **If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.**

  **ERROR OBJECTS** 

  *Error objects can help you find where your mistakes are and browsers have tools to help you read them*

 *ERROR OBJECTS CONTI NUED*

 **Syntax Error SYNTAX IS NOT CORRECT This is caused by incorrect use of the rules of the language. It is often the result of a simple typo: SyntaxError: Unexpect ed EOF ,SyntaxError: Expected token ' ) ' ,SyntaxError: Expected token ']'**

 **A DEBUGGING WORKFLOW**

 **Debugging is about deduction: eliminating potential causes of an error.** 

**WHERE IS THE PROBLEM?** 
**First, should try to can narrow down the area where the problem seems to be. In a long script, this is especially important.**

1. Look at the error message, it tells you: 

* The relevant script that caused the problem.

* The line number where it became a problem for the interpreter. (As you will see, the cause of the error may be earlier in a script; but this is the point at which the script could not continue.) 

* The type of error (although the underlying cause of the error may be different). 

2. Check how far the script is running. Use tools to write messages to the console to tell how far your script has executed. 

3. Use breakpoints where things are going wrong. They let you pause execution and inspect the values that are stored in variables


**WHAT EXACTLY IS THE PROBLEM?**

*Once you think that you might know the rough area in which your problem is located, you can then try to find the actual line of code that is causing the error*

1. When you have set breakpoints, you can see if the variables around them have the values you would expect them to. If not, look earlier in the script. 

2. Break down I break out parts of the code to test smaller pieces of the functionality. 

* Write values of variables into the console. 

* Calrfunctions from the console to check if they are returning what you would expect them to.

* Check if objects exist and have the methods I properties that you think they do. 

3. Check the number of parameters for a function, or the number of items in an array. 

# HOW TO LOOK AT ERRORS IN CHROME 

*The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.*

**If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.** 

**Debugging is the process of finding errors. It involves a process of deduction.**

**The console helps narrow down the area in which the error is located, so you can try to find the exact error.**

**JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.** 

*If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback*