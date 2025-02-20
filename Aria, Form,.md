February 11 Notes

Websites:
https://StackOverflow.com
https://flexboxfroggy.com
-study some Regex expressions
-"google style "a" to look like a button

Aria-SCEO-accessibility for webpages on the internet
![[Pasted image 20250211183313.png]]

![[Pasted image 20250211184059.png]]
**when using javascipt you might not need this** so just add the #

![[Pasted image 20250211184148.png]]
**GET**
a request to a server/website...you are saying get this information

![[Pasted image 20250211184225.png]]
**POST**
sending information to a database

***GOOD PRACTISE TO ACCESS YOUR STUFF IN JS BY ADDING AN ID***
![[Pasted image 20250211184503.png]]

**LABEL**
in-line elements. ( to fix the horizontal:
style =display: block
using div)
creating a .form and link external style sheet then add **FLEX BOX**
![[Pasted image 20250211185132.png]]

![[Pasted image 20250211185215.png]]
flex box-google tower defense to train !!!!!!!!!!!!!!

**INPUT**
-radio is a good one to look up
-***name**
access it by the id marathon  and the name attribute.....its how we access the data

*make sure your label is wired up to your name*

**EMAIL**
![[Pasted image 20250211185747.png]]


MEDIA QUERIES-help you change the sizing depending on device type..mobile, comp.

*gap pushes them apart in css*

**TEXTAREA**
a way to write long messages
its not an input field
![[Pasted image 20250211190337.png]]
you can change the size with rows

js-once unfocused you can make it snap back to a set size. 

**required attribut**e
so you can submit the form unless its filled out
![[Pasted image 20250211190632.png]]
called default validation
 **min and max**
 they can only enter a certain number of characters
 ![[Pasted image 20250211190726.png]]
 *HTML validation can be hackedin the dev tools...so make sure to use JS validation*

**REGEX**
WATCH YOUTUBE VIDEO.
for document regulation.   like password and email. 

**SELECT**
![[Pasted image 20250211191219.png]]
the value is what gets sent to JS
OR 
put a string like "male"
*make sure its lowercase*
![[Pasted image 20250211191354.png]]


**BUTTON**
semantics-says dont use input for button.
![[Pasted image 20250211191541.png]]
NOPE!!! dont do that...

*try not to use a button outside of a form*

-you can add an anchor tag. and style your button in css

you can also google ......."style a to look like button"
and use some elses problem of styling a button.

hover-makes the color change when your hover iver with mouse.


**HOW TO SEND A MESSAGE TO GOOGLE**
ACTION-HTTPS://GOOGLE.COM/"
-look on google to see their url path and query. 
(rewatch presentation)

![[Pasted image 20250211192537.png]]
-change id to search form

**POST**
JASON


**DROPDOWN MENU**
-in a label
-use select
-option value=

OR
you can put your label on its on line wired up with an id linking it to your selector. 



**ARIA**
BOOTSTRAP DOCUMENTATION SHOWS MORE INFO
MDN DOCS

-DESCRIBE BY
-DISABLE
-ARIA CURRENT
(for webscrapers.. and accessibility readers)

***5 IMPORTANT:***

![[Pasted image 20250211201529.png]]

(add more from mdn docs)
(could take about a year to master this)
Resume option:
a developer who adheres to SCEO becomes i believe in everyone being able to access the internet

or be just a CSS developer... you can pick which kind of developer you want to be a focus on to study to master. 

REQUIRED-
![[Pasted image 20250211194556.png]]
(when toggling on and off and skipping over)

LABELLED BY
ARIA WILL WIRE TO THE FORM
![[Pasted image 20250211194851.png]]
![[Pasted image 20250211195155.png]]

WHEN USING A PASSWORD:
![[Pasted image 20250211195220.png]]
to make this actually connect to the password in the form. 
add ariadescribedby =![[Pasted image 20250211195401.png]]
![[Pasted image 20250211195518.png]]


**ROLL ATTRIBUTE**
it describes what something is for

to tell a user the a change was made
you can use output
![[Pasted image 20250211195633.png]]
this would be inserted by javascript...not in your HTML

![[Pasted image 20250211195718.png]]
ARIA LIVE AND ROLE BOTH DO SOMETHING SIMILAR
-IT WILL SAY HEY THIS HAS BEEN SUBMITTED. 

**ARIA INVALID**
THEN SET IT TO TRUE....FOR WHEN THERE IS AN ERROR.
( add aname and id)
-for invalid email... or email to short.
to implent correctly you will need JS.
![[Pasted image 20250211200826.png]]
here is the JS IT NEEDS:
![[Pasted image 20250211200700.png]]

THEN YOU WOULD HAVE JS TOGGLE THE TRUE ON THE HTML TO FALSE.

(YOU ALSO HAVE ACCESS IN JS TO PASSWORD AND ATTRIBUTES ETC WITH CLASSLIST)

ARIA. SEARCH PAGE TO HELP SCREEN READERS ACCESIBILTY

practise: stack overflow gives already solves problems

assignment: see if i can put all 5 arias
-this assinments can be turned in to a blog post. 
"this is what i learned today"
first 6 months of learning to code and then post to linkedin....he did this but then took it down bc he felt cringy...but great practise and fun.
