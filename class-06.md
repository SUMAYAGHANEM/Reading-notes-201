# Object Literals:
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, <P>
* variables and functions take on new names. IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES <P>
* iN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS <P>
**The Object literal notation:**<P>
is basically an array of key:value pairs, with a colon separating the keys and values, and a comma after every key:value pair,<P>
  except for the last, just like a regular array. Values created with anonymous functions are methods of your object.<P>

**you can access the object using dot notation , you can access the properities using the square brackets**<P> 

# Document Object Model<P>
specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.<P>
**The DOM is called an object model because the model (the DOM tree) is made of objects.**<P>
It consists of four main types of nodes. : <P>
* THE DOCUMENT NODE<P>
* ELEMENT NODES<P>
* ATTRIBUTE NODES <P>
* TEXT NODES <P>
![tree](https://res.cloudinary.com/practicaldev/image/fetch/s--B2Ts1hyb--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/http://i67.tinypic.com/2nqegt2.jpg)<P>
  : ACCESS THE ELEMENTS<P>
  * sELECT AN INDIVIDUAL ELEMENT NODE : by ID <P>
  * SELECT MULTIPLE ELEMENTS (NODELISTS) : by class<P>
  * TRAVERSING BETWEEN ELEMENT NODES : parentNode<P>
 WORK W ITH THOSE ELEMENTS :<P>
  * ACCESS/ UPDATE TEXT NODES <P>
  * WORK W ITH HTML CONTENT <P>
  * ACCESS OR UPDATE ATTRIBUTE VALUES <P>

LOOPING THROUGH A NODELIST :<P>
If you want to apply the same code to numerous elements, looping through a Nodelist is a powerful technique. <P>
![loop](https://res.cloudinary.com/raymons/image/upload/w_1600/q_auto,f_auto/loop-over-nodelist-queryselectorall-javascript.png)<P>

ACCESS & UPDATE TEXT WITH TEXTCONTENT<P>
The textContent property allows you to collect or update just the text that is in the containing element (and its children). (& INN ERTEXT) <P>

Creating New HTML Elements (Nodes)<P>
To add a new element to the HTML DOM, you must create the element (element node) first, and then append it to an existing element.<P>
Removing Existing HTML Elements<P>
To remove an HTML element, use the remove( ) method:<P>

![remove](https://dart.dev/tutorials/web/images/remove-element.png)<P>

**DOM MANIPULATION** : refers to using a set of methods and properties to access, create, and update elements and text nodes. <P>
ADVANTAGES <P>
• It is suited to changing one element from a DOM <P>
fragment where there are many siblings. <P>
• It does not affect event handlers. <P>
• It easily allows a script to add elements <P>
incrementally (when you do not want to alter a lot <P>
of code at once). <P>
DISADVANTAGES <P>
• If you have to make a lot of changes to the<P> 
content of a page, it is slower than i nnerHTML. <P>
• You need to write more code to achieve the same <P>
thing compared with i nnerHTML. <P>

*Browsers offer tools for viewing the DOM tree .* <P>
*An element node can contain multiple text nodes and <P>
child elements that are siblings of each other*<P>
