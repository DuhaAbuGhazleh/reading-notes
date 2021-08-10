

## 1- Transforms



**Transform Syntax**

The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.


Example :

`div {`

  `-webkit-transform: scale(1.5);`

 ` -moz-transform: scale(1.5);`

 ` -o-transform: scale(1.5);`

 `transform: scale(1.5);`

`}`

The transform property comes in two different settings

1-  two-dimensional 

- **2D Rotate:** ability to rotate an element from 0 to 360 degrees

- **2D Scale**: 

to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

- **2D Translate**

The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.

- **2D Skew**

The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.

- **Transform Origin**


 the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically.
 
  To change this default origin position the transform-origin property may be used

2-  three-dimensional. 

- 3D rotate
- 3D scale 
- 3D Translate
- 3D Skew
- Transform Origin


## Transitions & Animations

Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

**Transitions**

an element must have a change in state, and different styles must be identified for each state. 

The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

- There are four transition related properties in total, including:

`transition-property`

 `transition-duration`
 
  `transition-timing-function`
  
  ` transition-delay.` 


  ## 8 simple CSS3 transitions that will wow your users

  1- 1. Fade in

  It’s a great way to emphasize functionality or draw attention to a call to action.

  2- Change color

  3-Grow & Shrink

 ` .grow:hover`

`{`

 ` -webkit-transform: scale(1.3);`

 ` -ms-transform: scale(1.3);`

`transform: scale(1.3);`

`}`




  4-Rotate elements

  5-Square to circle

  6-3D shadow

  7-Swing

  8-Inset border

  [for more information and to see code for each one ](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)


## more about style 
  - [6 Buttons animated](https://codepen.io/retyui/pen/ByoaXV)
- [CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/oAfae)
- [404](https://codepen.io/kieranfivestars/pen/MYdQxX)
-[ Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/gCfBv)





