# charts in js : 

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
Setting up
![dsfsd](https://miro.medium.com/max/3748/1*toepgVwopga9TYFpSkSxXw.png)

* The first thing we need to do is download Chart.js
* Drawing a line chart :To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart
* Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:
* Inside the same script tags we need to create our data

**Drawing a pie chart**
* we need the canvas element
* Next, we need to get the context and to instantiate the chart
* Next we need to create the data.
![fdgdfg](https://miro.medium.com/max/679/1*c9QQgpC9YnznJWFOjWF7tA.png)

**Drawing a bar chart**
* we add the canvas element
* we retrieve the element and create the graph
* we add in the bar chart’s data

![sdfdsf](https://res.cloudinary.com/practicaldev/image/fetch/s--04Uz3pU---/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/pdg4eqlpz1hjjfwcdsxj.png)

chart code in js :

![scscsdgg](https://i.stack.imgur.com/TMX9U.png)

# Applying styles and colors

 we will explore the canvas options we have at our disposal to make our drawings a little more attractive
 **Colors :**
 there are two important properties we can use: 
 * fillStyle :Sets the style used when filling shapes.
 * strokeStyle : Sets the style for shapes' outlines.
  
  example code :
  function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  for (var i = 0; i < 6; i++) {
    for (var j = 0; j < 6; j++) {
      ctx.fillStyle = 'rgb(' + Math.floor(255 - 42.5 * i) + ', ' +
                       Math.floor(255 - 42.5 * j) + ', 0)';
      ctx.fillRect(j * 25, i * 25, 25, 25);
    }
  }
}

-**Transparency**
 This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.
 
 **Line styles**
There are several properties which allow us to style lines.

lineWidth = value
Sets the width of lines drawn in the future.
lineCap = type
Sets the appearance of the ends of lines.
lineJoin = type
Sets the appearance of the "corners" where lines meet.
miterLimit = value
Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
getLineDash()
Returns the current line dash pattern array containing an even number of non-negative numbers.
setLineDash(segments)
Sets the current line dash pattern.
lineDashOffset = value
Specifies where to start a dash array on a line.

![fdgg](https://mdn.mozillademos.org/files/239/Canvas_linewidth.png)




