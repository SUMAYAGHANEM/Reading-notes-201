# images :
**How to change image size in CSS?** <P>
We can resize the image by specifying the width and height of an image. A common solution is to use the max-width: 100%; and height: auto; <P>
so that large images do not exceed the width of their container. The max-width and max-height properties of CSS works better, but they are not supported in many browsers.<P>

**aligning images using css**<P>
Aligning an image means to position the image at center, left and right. We can use the float property and text-align property for the alignment of images. If the image is in<P>
the div element, then we can use the text-align property for aligning the image in the div<P>

![s}(https://s3.amazonaws.com/impressivewebs/2011-12/vertical-align-pic.jpg)<P>

**Centering images<P>
Using Css**<P>
1: On the containing element, <P>
you can use the text - align<P>
property with a value of center.<P>
2: On the image itself, you can <P>
use the use the margin property <P>
and set the values of the left and <P>
right margins to auto<P>
![s](https://css-tricks.com/wp-content/uploads/2011/10/centered.gif)<P>

**Background Images**<P>
The background-image<P>
property allows you to place <P>
an image behind any HTML <P>
element. This could be the entire <P>
page or just part of the page<P>

example :<P>
p {<P>
background-image: ur l(" images/pattern.gif");}<P>
<P>
**Repeating Images** <P>
* repeat<P>
The background image is <P>
repeated both horizontally and <P>
vertically <P>
* repeat-x<P>
The image is repeated <P>
horizontally only<P>
* repeat-y<P>
The image is repeated vertically <P>
only.<P>
* no-repeat<P>
The image is only shown once.<P>

**Background Position<P>
**

When an image is not being <P>
repeated, you can use the <P>
background-position<P>
property to specify where in the <P>
browser window the background <P>
image should be placed. <P>
![df](https://bitsofco.de/content/images/2016/06/position.png)<P>

**Image Rollovers**<P>
Using CSS, it is possible to create <P>
a link or button that changes to a <P>
second style when a user moves <P>
their mouse over it <P>

example :<P>
<style><P>
    /*<P>
      Rollover Image<P>
     */<P>
    .figure {<P>
        position: relative;<P>
        width: 360px; /* can be omitted for a regular non-lazy image */<P>
        max-width: 100%;<P>
    }<P>
    .figure img.image-hover {<P>
      position: absolute;<P>
      top: 0;<P><P>
      right: 0;<P>
      left: 0;<P>
      bottom: 0;<P>
      object-fit: contain;<P>
      opacity: 0;<P>
      transition: opacity .2s;<P>
    }<P>
    .figure:hover img.image-hover {<P>
      opacity: 1;<P>
    }<P>
</style><P>

# Practical Information :<P>
Search engine optimization (or <P>
SEO) is the practice of trying <P>
to help your site appear nearer <P>
the top of search engine results <P>
when people look for the topics <P>
that your website covers.<P>

**On-Page SEO**<P>
In every page of your website there are seven key places where keywords <P>
(the words people might search on to find your site) can appear in order <P>
to improve its findability<P>
: Page Title<P>
2: URL / Web Address<P>
3: Headings<P>
4: Text<P>
5: Link Text<P>
6: Image Alt Text<P>
7: Page Descriptions<P>
