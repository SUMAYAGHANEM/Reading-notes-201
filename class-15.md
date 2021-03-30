# Transforms in css
* what is :  ways to position and alter elements
*  by the : transform property.
 * comes in two different settings: two-dimensional and three-dimensiona
  **Transform Syntax**
 * including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}

**2D Transforms**
![fdg](https://s3.amazonaws.com/webucator-how-tos/2311.png)

. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes
The transform property accepts a handful of different values:
* The rotate value provides the ability to rotate an element from 0 to 360 degrees.

* scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

* The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
* skew, is used to distort elements on the horizontal axis, vertical axis, or both.

**Combining Transform**
It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example

Perspective Depth Value : 
![dsfdsgh](https://www.includehelp.com/code-snippets/Images/perspective-of-an-element-in-css.jpg)
The perspective value can be set as none or a length measurement. The none value turns off any perspective, while the length value will set the depth of the perspective. The higher the value, the further away the perspective appears

**3D Transforms**
![gjhjhgj](https://tipsmake.com/data/images/3d-transform-in-css-picture-1-jtznOkrOW.jpg)

* With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ.
* By using the scaleZ three-dimensional transform elements may be scaled on the z axis. This isn’t extremely exciting when no other three-dimensional transforms are in place, as there is nothing in particular to scale.
* Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element.
* Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale. Elements may be skewed on the x and y axis, then transformed three-dimensionally as wished, but they cannot be skewed on the z axis.


**css transitions**:
1. Fade in
Fade in effects are coded in two steps: first, you set the initial state; next, you set the change, for example on hove
.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}
2.Change color
3.Grow & Shrink To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.
4. Rotate elements Give your div the class “rotate”
5. 5. Square to circle
6. 3D shadowThis effect is achieved by adding a box shadow, and then moving the element on the x axis using the transform and translate properties so that it appears to grow out of the screen.
7. Swing  
8. Inset border

![dhgjk](https://i.stack.imgur.com/fgsas.png)
