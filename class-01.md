
 # Introductory HTML and JavaScript

 ## 1- HTML

   ### **- Structure**


   - HTML elements: are usually made up of two tags an opening tag and a closing tag. (The closing tag has an extra forward slash in it.)
      
  - HTML Uses Elements to Describe the Structure of Pages
  - Each element has an opening tag and a closing tag. Tags act like containers. They tell you something about the information that lies between their opening and closing tags.
       **Example:**
       
    - The opening ` <html>` tag indicates that anything between it and a closing `</html>` tag is HTML code.

    - The `<body>` tag indicates that anything between it and the closing
     `</body>` tag should be shown inside the main browser window.
      
 - Attributes provide additional information about the contents of an element. 
       
 - Attributes appear on the opening tag of the element and are  made up of two parts  separated by an equals sign

    * The name  indicates what kind of extra information you are supplying about the element's content. It should be written in lowercase.

    * The value is the information or setting for the attribute. It should be placed in double quotes. 

      
 **Creating a Web Page on a PC**   
   
  * Use  Notepad
  * Type code
  * Go to the File menu and select Save as... 
  * Save this file as (name.html)
  * Make sure that the Save as type drop down has All Files selected.
  * Start your web browser. Go to the File menu and select Open. Browse to the file that you just created, select it and click on the Open button.

 **Creating a Web Page on a Mac**

  * Use  TextEdit.
  * Type the code
  * go to the File menu and select Save as...
  * Save this file as (name.html)
  * You want to select the `Use.html` button. 
  * Next, start your web browser, go to the File menu, and select Open. You should browse to the file that you just created, select it and click on the Open button


   ### **- Extra Markup**



  
  
Each new version was designed to be an improvement on the last (with new elements and attributes added and older code removed).

Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using.


Extra Markup |About it    | How to use
------------ | -------------  | -------------
Comments |when you add a comment to your code that will not be visible in the user's browser, comments will make code much easier to understand,Comments can also be used around blocks of code to stop that code from being displayed in the browser.   | `<!-- comment goes here -->`
ID Attribute | It is used to uniquely identify that element from other elements on the page | `<p id="pullquote">Every time</p>`
Class Attribute | Every HTML element can also carry a class attribute. a way to identify several elements as being different from the other elements on the page. | `<p class="important"> Example </p>` `<p class="important admittance">Hours</p>`
Block Elements | elements will always appear to start on a new line in the browser window | `<h1>`, `<p>`, `<ul>`, and `<li>`.
inline elements | always appear to continue on the same line as their neighbouring elements. | `<a>`, `<b>`, `<em>`, and `<img>`.
Grouping Text & Elements In a Block | 1-The `<div>` element allows you to group a set of elements together in one block-level box.  2-The` <span>` element acts like an inline equivalent of the `<div>`element. |   ![image](https://user-images.githubusercontent.com/86604676/126880086-a4347629-dc53-492f-9742-882ecf177f4a.png)  ![image](https://user-images.githubusercontent.com/86604676/126880157-302d22ff-7a9f-47a7-845d-116527341e2c.png)
IFrames |  An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame. | ![image](https://user-images.githubusercontent.com/86604676/126880225-19e71ebc-90d1-4e16-a2b4-d371367ef70f.png)
`<META>` | The `<meta>` element lives inside the` <head>` element and contains information about that web page. |   ![image](https://user-images.githubusercontent.com/86604676/126880270-0c63fd23-b13e-4688-b625-ee19b031f604.png)
Escape Characters | Therefore, if you want these characters to appear on your page you need to use what are termed "escape" character |  For example, to write a left angled bracket, you can use either `&lt;` or `&#60;`


  

  



   **- HTML5 Layout**


HTML5 is introducing a new set of elements that help define the structure of a page.


  - *Traditional HTML Layouts*

For a long time, web page authors used `<div>` elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the `<div>` element in the structure of the page.


  ![image](https://user-images.githubusercontent.com/86604676/126880530-3220256f-670e-4278-9167-e169103847d2.png)


  - HTML5 layout  lements and their uses

HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them.


  ![html5 elements](https://user-images.githubusercontent.com/86604676/126880545-8087c8b0-a7aa-4b57-bda2-9d6b3d021e09.png)



**many of the `<div>` elements have been replaced by new HTML5 layout elements.**

  1- Headers & Footers

used for: 
 
  ● The main header or footer
that appears at the top or
bottom of every page on the
site.

  ● A header or footer for an
individual `<article>` or
`<section>` within the page

2- Navigation
`<nav>`

* The `<nav>` element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.

3- Articles
`<article>`

acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.

If a page contains several articles
(or even summaries of several
articles), then each individual
article would live inside its own
`<article>` element.

4- Asides

`<aside>`
has two
purposes, depending on whether
it is inside an <article>
element or not.

* When the `<aside>` element
is used inside an `<article>`
element, it should contain
information that is related to the
article but not essential to its
overall meaning. For example, a
pullquote or glossary might be
considered as an aside to the
article it relates to.


* When the `<aside>` element is
used outside of an `<article>`
element, it acts as a container
for content that is related to
the entire page. For example,
it might contain links to other
sections of the site, a list of
recent posts, a search box, or
recent tweets by the author.

5- Sections
`<section>`

The` <section>` element groups
related content together, and
typically each section would
have its own heading.

- groups related items together,
-can be
used to split the article up into
separate sections.

6- Heading Groups
`<hgroup>`

The purpose of the `<hgroup>`
element is to group together a
set of one or more `<h1>` through
`<h6>` elements so that they are
treated as one single heading.


7- Figures
`<figure> <figcaption>`

Examples of usage include:

● Images

● Videos

● Graphs

● Diagrams

● Code samples

● Text that supports the main body of an article

The `<figure>` element should
also contain a `<figcaption>`
element which provides a text
decription for the content of
the `<figure>` element.

8- Sectioning Elements
`<div>`

an important way to
group together related elements,


9- Linking Around
Block-Level Elements

HTML5 allows web page authors
to place an <a> element around
a block level element that
contains child elements. This
allows you to turn an entire block
into a link.


   **- Process & Design**


   
* It's important to understand who is your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.
* Site maps allow you to plan the structure of a site.
![map](https://user-images.githubusercontent.com/86604676/126880797-1f0d9d40-1fdb-441b-bb2c-be39e1aacc6f.png)


* Wireframes allow you to organize the information that
will need to go on each page.

![wireframe](https://user-images.githubusercontent.com/86604676/126880817-9861abce-dd0e-4317-8ca2-c53233874ee5.png)

* Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
* You can differentiate between pieces of information
using size, color, and style.
* You can use grouping and similarity to help simplify
the information you present.



 ## 2- JavaScript

 ### **The ABC of Programming**


 

 #### **A ** What is a script and how do I create one?

 * A SCRIPT IS A SERI ES OF INSTRUCTIONS that a
computer can follow to achieve a goal.


 * WRITING A SCRIPT

 To write a script, you need to first
state your goal and then list the
tasks that need to be completed in
order to achieve it.


Start with the big picture of what
you want to achieve, and break
that down into smaller steps.

1: DEFINE THE GOAL
First, you need to define the task you want to
achieve. You can think of this as a puzzle for the
computer to solve.

2: DESIGN THE SCRIPT
To design a script you split the goal out into a series
of tasks that are going to be involved in solving this
puzzle. This can be represented using a flowchart.

3: CODE EACH STEP
Each of the steps needs to be written in a
programming language that the compu ter
understands. In our case, this is JavaScript.



#### **B** How do computers fit in with the world around them?

HOW A BROWSER
SEES A WEB PAGE
In order to understand how you can change the content of an HTML
page using JavaScript, you need to know how a browser interprets the
HTML code and applies styling to it.

1: RECEIVE A PAGE AS
HTML CODE
Each page on a website can be
seen as a separate document .
So, the web consists of many
sites, each made up of one or
more documents.


2: CREATE A MODEL OF
THE PAGE AND STORE
IT IN MEMORY
The model shown on the right
hand page is a representation
of one very basic page. Its
structure is reminiscent of a
family tree. At the top of the
model is a document object,
which represents the whole
document.
Beneath the document object
each box is called a node. Each
of these nodes is another object.
This example features three
types of nodes representing
elements, text within the
elements, and attribute.

3: USE A RENDERING
ENGINE TO SHOW THE
PAGE ON SCREEN
If there is no CSS, the rendering
engine will apply default styles
to HTML elements. However,
the HTML code for this example
links to a CSS style sheet, so the
browser requests that file and
displays the page accordingly.
When the browser receives
CSS rules, the rendering engine
processes them and applies
each rule to its corresponding
elements. This is how the
browser positions the elements
in the correct place, with the
right colors, fonts, and so on.



#### **C** How do I write a script for a web page?


- `<html>`
CONTENT LAYER
. html files

This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics.

- PRESENTATION LAYER
.css files

The CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.).

- BEHAVIOR LAYER
.js files


This is where we can change
how the page behaves, adding
interact ivity. We will aim to keep
as much of our JavaScript as
possible in separate files.

**PROGRESSIVE
ENHANCEMENT**


These three layers form the basis of a popular
approach to building web pages called
progressive enhancement.


- It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.


- The HTML `<script>` element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the `<link>` element can be used to load a CSS file).

- If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created