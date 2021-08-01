# Object-Oriented Programming, HTML Tables

1- Domain Modeling:

 is the process of creating a conceptual model in code for a specific problem.  referred to as an object-oriented model.

**Define a constructor and initialize properties**

a constructor function: to define the same properties 

**object-oriented**
- The new keyword instantiates (i.e. creates) an object.

- The constructor function initializes properties inside that object using the this variable.

- The object is stored in a variable for later use.

**Generate random numbers**
`a Math.random()` function 

- Model its attributes with a constructor function that defines and initializes properties. 

-Model its behaviors with small methods that focus on doing one job well.

-Create instances using the new keyword followed by a call to a constructor function.

-Store the newly created object in a variable so you can access its properties and methods from outside.

-Use the this variable within methods so you can access the object's properties and methods from inside.





2- Tables:

represents information in a grid format.

**Basic Table St ructure**


`<table>`
 used to create a table. 
 
`<`tr>`
to indicate the start of each row 

It is followed by one or more
`<td> `

`<td>`

to represented each cell

`<th>`

used to represent the heading for either a column or
a row.

For long tables you can split the table into a <thead>,
<tbody>, and <tfoot>.

3- Functions, Methods, and Objects

**Object Properties**

The named values, in JavaScript objects, are called properties.

**Object Methods**

Methods are actions that can be performed on objects.


 **create new objects**:

- Create a single object, using an object literal.

example: `const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};`

-Create a single object, with the keyword `new.`

`const person = new Object();`

-Define an object constructor, and then create objects of the constructed type.

-reate an object using `Object.create().`
