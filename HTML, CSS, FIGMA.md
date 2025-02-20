FIGMA & CSS

#remember don't put content in the head. 

What goes in the head?
links to CSS, title, meta, JS*, <style, favicon,

#remember the only thing that goes outside of the body > head

#remember HTML wraps around the head and body

**MDN GIVES A LIST OF SEMANTIC ELEMENTS THAT CAN BE USED. 


**ADD EVENT LISTENER** ARE DIFFICULT TO USE
-AND CAN ONLY DO ONE FUNCTION CALL ON EACH ONE
GLOBAL ATTRIBUTES-
-onclick
-onmousewheel event will change the way the page behaves with a mouse

**HEADER**
-you might see a ul and li inside
###a good example would be home about us and shop
![[Pasted image 20250210185549.png]]
-you technically could have two headers
-your h1 could go in header
- h1 could even go in between the head and body
- h1 always has to go at the top change style it to be smaller or bigger

**H1**
-It can be a very small and placed off the page but it has to be there and first in heirarchy for search engines. 
HONEYPOT-
-a technic for putting it off the page could be placed in a form. AND placed off the page for bots trying to submit a form. 
**manipulating things to be pushed off the page**
( you can use CSS -translate S-and then set it -1000 pixels
or with opacity)
other ways to manipulate this:
transform
absolute
translate s
overlap


**Lots of content**
-in your main throw all the content in sections and use section elements
-use article also

**Article**
multiple articles can each have an h1
*mdm has good info*
-address element
-publication date

**Footer**
*mdn docs has ways to add an address*

**Aside**
-use this as a way to add to an article for an aside but of information #something not directly related
-he uses it for blog posts that coincide with article

**DIV AND SPAN**
(NON-sematic elements)

**DIV**
#remember never put a div in a p> element
*instead use the **pre** element*
-use this for layout as much as you want, but make sure arent using them without an element. 
-use for styling inside of your sections.

**SPAN**
-It can go inside of a paragraph element because it doesnt break up the text.  DIVS CANT
 CSS span class = ""

**PRE AND CODE**
![[Pasted image 20250210193426.png]]
it has to be used with code
*this tells screen readers that this is code*

*it keeps track of the indentation of things*
![[Pasted image 20250210193556.png]]


**HREF**
reference mdn docs when you use it


#contant **WE SHOULD BE USING MDN DOCS FOR EVERYTHING WE USE AT THIS POINT. WE WANT TO BE STUDYING IN DEPTH AS WE WORK.


**FAVICON**
MDN says how to get the site.
*has emoji's*
*Generates text*
*customization*
*you can make your favicon your initials with different colors and fonts*
*you can even add other images and drop it into the link that will change your favicon icon*
![[Pasted image 20250210195451.png]]
-ideally have a 16 px image for your favicon icon
-grab that sized one and drag it into vs code
-put it inside of a link inside head of website
-***smaller the better and contrast is BETTER***



**SCRIPT**
![[Pasted image 20250210195642.png]]
-if you dont add your script to the bottom above footer you need to write **defer**

***PRACTISE DEMO HTML:***

-he uses GRID AND FLEX BOX in his header when adding a lot of content. 

#remember grid and flex box always go together


**MARGIN**
*PUSHES ELEMENTS APART*
..like a div and p apart vertically or horizontally

**PADDING**
*INCREASES THE SPACE BETWEEN THE CONTENT AND THE BORDER*
be careful when using divs and images because the child inside of the parent if it larger will still spill over and be larger even if hard coded at certain width and height.

**SPECIFICITY**
ID SELECTORS WILL ALWAYS BEAT CLASS BC ID'S HAVE A higher specificity

**CSS**
CLASS PERIOD .
ID NUMBER #


**WILD CARD ELEMENT-APPLIES TO ALL ELEMENTS ON THE PAGE WHEN USED**
**BOX SIZING**
![[Pasted image 20250210202106.png]]
*use this every time if not using bootstrap or something like it **


**DISPLAY BLOCK**
-ELEMENTS THAT HAVE BLOCK BY DEFAULT:
DIV
-THEY TAKE UP THE ENTIRE WIDTH OF SPACE ON THE WEBSITE. 
*research mdn*

**icons**
Try putting your social media icons in the footer. 


ASSIGNMENT OF REVIEWING HTML:
PRE ELEMENT
HOKU POEM OR CODE WOULD BE GOOD TO USE FOR ASSIGNMENT


