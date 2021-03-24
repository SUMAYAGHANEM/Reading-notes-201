# debugging : 
order of execution: (the order in which statements are processed
**EXECUT.ION CONTEXTS**
There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 
EXECUTION CONTEXT :
* GLOBAL CONTEXT
* FUNCTION CONTEXT
* EVAL CONTEXT (NOT SHOWN) 
**VARIABLE SCOPE**
* GLOBAL SCOPE
* FUNCTION-LEVEL SCOPE

**A stack** is a data structure that holds a list of elements,
Last In, First out, meaning that the most recently added element is the first one to remove.
 A stack has two main operations that occur only at the top of the stack: 
 * push 
 *  pop
 *  ![s](https://i.stack.imgur.com/xAQPR.png)

**UNDERSTANDING 
SCOPE**
In the interpreter, each execution context has its own va ri ables object. 
It holds the variables, functions, and parameters available within it. 
Each execution context can also access its parent's v a ri ables object

**UNDERSTANDING ERRORS**
If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code

**ERROR OBJECTS**
Error objects can help you find where your mistakes are 
and browsers have tools to help you read them. 
**built-in error**
* Error 
* Syntax Error 
* DESCRIPTION 
* Generic error -
* TypeError 
* Range Error 
* URI Error 
* EvalEr r or 

**HOW TO DEAL WITH ERRORS**
1.DEBUG THE SCRIPT TO FIX ERRORS : you will need to 
debug the code, track down the source of the error, 
and fix it. 
2.HANDLE ERRORS GRACEFULLY 
You can handle errors gracefully using try, catch, 
throw, and f i na 1 ly statements.
**A DEBUGGING 
WORKFLOW**
1. Look at the error message, it tells you
2. Use breakpoints where things are going wrong. 
3.  Check how far the script is running. 
4.  
5. 
