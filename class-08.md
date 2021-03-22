# CSS Layout
Building Blocks : CSS treats each HTML element as if it is in its own box.<P>
This box will either be :<P>
* a block-level :  start on a new line and act as the main building blocks of any layout<P>
* box or an inline box : while inline boxes flow between surrounding text<P>
**You can control how much space each box takes up by setting the width of the boxes** <P>
**To separate boxes, you can use borders, margins, padding, and background colors.**<P>
 
Containing Elements : It is common to group a number of elements together inside a < div >(or other block-level) element. <P>
  
  ![a](https://i0.wp.com/onaircode.com/wp-content/uploads/2019/09/padding-versus-margin.jpg?resize=1080%2C675&ssl=1)<P>

**positioning schemes:**<P>
* Normal flow<P>
* Relative Positioning<P>
* bsolute positioning<P>
box offset properties : to tell the browser how far from the top or bottom and left or right it should be placed<P>
* Fixed Positioning <P>
* Floating Elements<P>

![p](https://www.csssolid.com/images/csspositions/css-position-all.png)<P>

*A lot of layouts place boxes next to each other. The floatproperty is commonly used to achieve this.*<P>
Clearing Floats : The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of the box.<P>
  
  **problem** : If a containing element onlycontains floated elements, some browsers will treat it as if it is zero pixels tall.
  **solution** : CSS solution is adding  two CSS rules to the containing element,example : 
● The overflow property is given a value auto.
● The width property is set to 100%.

**Creating Multi-Column Layouts with Floats** : 
Many web pages use multiple columns in their design. This is achieved by using a < div>element to represent each column. 
The following three CSS properties are used to position the columns next to each other:
* width
* float
* margin
![s](https://i2.wp.com/css-tricks.com/wp-content/uploads/2021/02/web-text-wrap.png?resize=540%2C270&ssl=1)
