
## Chart.js API.

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.


## Chart.js

**Creating a Chart**


It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>`node to render the chart.


## Canvas API.

1- **Basic usage of canvas**

- The` <canvas>` element

`<canvas id="tutorial" width="150" height="150"></canvas>`

- Fallback content

- Required `</canvas> `tag

**The rendering context**

The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES

**2- Drawing shapes with canvas**

you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.

**3-Applying styles and colors**

add different colors, line styles, gradients, patterns and shadows 

**4-Drawing text**

The canvas rendering context provides two methods to render text:

- `fillText(text, x, y [, maxWidth])`


Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

- `strokeText(text, x, y [, maxWidth])`


Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.