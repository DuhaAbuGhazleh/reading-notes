# Problem Domain, Objects, and the DOM

## 1- Understanding The Problem Domain 

**Why problem domains are hard**

 because you can’t really see what you are trying to build very clearly.  

 **understand the problem domain**

 is the hardest part of programming 

 you have to divide the problem to components that we have taken out of. 

 then try to solve each componant separatly 

 then gathering all componant

 **What can you do about it?**

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

- Make the problem domain easier
 - Get better at understanding the problem domain
 



## 2- Object Literals

Object : is the curly braces and thier contant 

Hotel : the object sorted in variable 

literals notation : easist and most popular way to creat object

dot notation or square brackets : to access the propreties or method of an object

`objectName.propertyName`

`var myCar = new Object();`
`myCar.make = 'Ford';`





## 3- Document Object Model


how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.


**caching DOM Queries:** the method that find element in DOM tree

 **when you need to work with element more than once**: you should use variable to store it 

 **storing variable:** mean store the location 

 **METHODS THAT RETURN A SINGLE ELEMENT NODE:**
- getElementByld`( ' id ')`

- querySel ector`(' 1css selector ')`

- getEl ement sByClassName`( 'class' )`

- getEl ementsByTagName`( ' tagName ')`

- querySelectorAll `( 'css selector ')`

summary


 Whenever a DOM query can return more than one
node, it will always return a Nadel i st.

From an element node, you can access and update its
content using properties such as textContent and
innerHTML or using DOM manipulation techniques.

An element node can contain multiple text nodes and
child elements that are siblings of each other.

In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).

Browsers offer tools for viewing the DOM tree .
