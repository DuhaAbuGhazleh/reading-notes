#  Forms and JS Events

The best known form on the web is probably the search box


 ## A-  Forms

to collect information from
visitors


**Form Controls**

- ADDING TEXT
  -Text input (single-line)

  - Password input

  - Text area (multi-line)

-  Ma king Choices

- Submitting Forms

- Uploading Files



**Form Structure**

- `<form>`
This element
should always carry the action
attribute and will usually have a
method and `id` attribute too.

- action

Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.

- method

Forms can be sent using one of
two methods:` get` or `post`.

**get**

short forms (such as search
boxes)

**post**

 ** allows users to upload a file
** is very long
** contains sensitive data
(e.g. passwords)
** adds information to, or
deletes information from, a
database


example 

`<form action="http://www.example.com/subscribe.php" method="get">  `
`<p>This is where the form controls will appear. </p>`
`</form>`

**`<input>`**

The `<input>` element is used
to create several different form
controls. The value of the type
attribute determines what kind
of input they will be creating.

such as 

1-  `type="text"`

When the type attribute has a
value of text, it creates a singleline
text input.

2- Password Input

`<input>`

`type="password"`

When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, 

`name`

The name attribute indicates
the name of the password input,
which is sent to the server with
the password the user enters.

`size, maxlength`

It can also carry the size and
maxlength attributes like the
the single-line text input.

## B-  Lists, Tables

- Bullet Point Styles

`list-style-type`

allows you to control the shape
or style of a bullet point (also
known as a marker).

 Images for Bullets

 `list-style-image`

 specify an image to act
as a bullet point using the
list-style-image property.

- Table Properties

`width` 

`padding` to set the space
between the border of each table
cell and its content

`text-transform` to convert the
content of the table headers to
uppercase

`letter-spacing`, font-size
to add additional styling to the
content of the table headers

`border-top, border-bottom`
to set borders above and below
the table headers

`text-align` to align the writing
to the left of some table cells and
to the right of the others


`:hover `to highlight a table row
when a user's mouse goes over it


*and there are more  Properties you can use it to make the table more interactive.*

## C- Events

Scripts often respond to these events by updating the content of the web page *(via the Document Object Model)* which makes the page feel more interactive.


The steps :

- inter action creat event 

- event trigger code : different code can be triggered when user interact with different part of the page 

- Code respond to the user

**DIFFERENT EVENT TYPES**

- UI EVENTS: Occur when a user interacts with the browser's

Such as : load , unload , error , resize 

- KEYBOARD EVENTS: Occur when a user interacts with the keyboard

such as : keydown , keyup, keypress

- MOUSE EVENTS : Occur when a user interacts with a mouse. trackpad, or touchscreen

such as : click 

**HOW EVENTS TRIGGER
JAVASCRIPT CODE**

1- Select t he element
node(s) you want the
script to respond to.

2- Indicate which event on
the selected node(s) will
trigger the response.  

3-  State the code you want
to run when the event
occurs.

**THREE WAYS TO BIND AN
EVENT TO AN ELEMENT**

1- HTML EVENT HANDLERS

`do not use ` This approach is
now considered bad practice


2- TRADITIONAL DOM EVENT HANDLERS

can only attach one function to each event handler.


3- DOM LEVEL 2 EVENT LISTENERS

the event
handler appears on the last line
of the JavaScript.

4- EVENT LISTENERS

can deal with more than function 

**the syntax**

`element .addEventlistener('event', functionName [, Boolean]) ;`

**The most commonly used events are W3C DOM
events**