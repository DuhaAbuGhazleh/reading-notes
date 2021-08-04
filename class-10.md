# Error Handling & Debugging

Determine what went wrong in your JavaScript and how to fix it:

1- THE CONSOLE &
DEV TOOLS

Tools built into the browser
that help you hunt for errors.


2- COMMON PROBLEMS

Common sources of errors,
and how to solve them.

3- HANDLING ERRORS

How code can deal with
potential errors gracefully.


**EXECUTION CONTEXT**

Every statement in a script lives in one of These execution contexts:

- GLOBAL CONTEXT: 

variable is declared outside a function, it can be used anywhere because it has global scope.


- FUNCTION CONTEXT: 

When a variable is declared within a function, it can only be used within that function.


**EXECUTION CONTEXT & HOISTING**

there are two phases
of activity:

1- PREPARE 

creste new scope , variable , function 
then determined the value of it 


2- EXECUTE

assign value , run the code of function , Execute statements

**ERROR OBJECTS**

- Error 

Generic error - the other errors
are all based upon this error 


- ReferenceError 

variable that is not declared or is
out of scope.

- TypeError

incorrect use of the rules of the
language.

- Range Error 

Numbers not in acceptable range

- URI Error

INCORRECT USE OF URI FUNCTIONS
If these characters are not escaped in URls, they will cause an error: / ? & I : ;



**HOW TO DEAL WITH ERRORS**


you can use Console
