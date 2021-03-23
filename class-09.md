# forms : 
penefite : 
* to enabling users to search
* forms also allow users to perform other functions online

![s](https://i2.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/01/HTML-Form.jpg?fit=1920%2C1080&ssl=1)

**form controls:**
There are several types of form controls that you can use to collect information from visitors to your site.
* ADDING TEXT
* Making Choices
* submitting Forms
* Uploading Files:

**how do forms work :**
* A user fills in a form and then presses a button to submit the information to the server.
* The name of each form control is sent to the server along with the value the user enters or selects.
* The server processes the information using a programming language
* The server creates a new page to send back to the browser based on the information received.
* ![s](https://img.webnots.com/2014/01/How-HTML-Form-Works.png)

A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element

**Form Structure**
< form > : always carry the < action > attribute :
Its valueis the URL for the page on the server that will receive the 
information in the form when it is submitted. ,
and can contain some methods : get or post. 

*Text Input:*
The <  input> element is used to create several different form controls.
The value of the typeattribute determines what kind of input they will be creating
*Password Input*
type=" password" 
When the type attribute has a value of password it creates a text box that acts just 
like a single-line text input, except the characters are blocked out.
*Radio Button*
type=" radio"
Radio buttons allow users to pick just one of a number of options.
*Checkbox*
type="checkbox"
Checkboxes allow users to select (and unselect) one or more options in answer to a question
*File Input Box*
type="file"This type of input creates a box that looks like a text input followed by a browse button. 

### Form Validation
give users messages if the form control has not been filled in correctly

# Lists, Tables and Forms
list-style-type:
The list-style-type property allows you to control the shape or style of a bullet point
* decimal
* decimal-leading-zero
* lower-alpha
* upper-alpha
* lower-roman

list-style-image:
You can specify an image to act as a bullet point using thelist-style-image property.
The value starts with the letters url and is followed by a pair of parentheses. Inside the parentheses, the path to the image is given inside double quotes.
![a](https://imgs.developpaper.com/imgs/2020224160838914.png)

**Table Properties**
* width
* padding
* text-transform
* letter-spacing, font-size
* border-top, border-bottom
* text-align
* background-color
* :hover

# Events in js : 
W hen you browse the web, your browser registers different 
types of events. It's the browser's way of saying, "Hey, this 
just happened." Your script can then respond to these events , usually by updating the content.

examples :
* load W eb page has finished loading 
* unload Web page is unloading (usually because a new page was requested) 
* error Browser encounters a JavaScript error or an asset doesn't exist 
* keydown User first presses a key (repeats while key is depressed) 
click User presses and releases a button over the same element 

**HOW EVENTS TRIGGER 
JAVASCRIPT CODE**
* Select t he element 
node(s) you want the 
script to respond to. 
* Select t he element 
node(s) you want the 
script to respond to. 
* State the code you want 
to run when the event 
occurs. 


