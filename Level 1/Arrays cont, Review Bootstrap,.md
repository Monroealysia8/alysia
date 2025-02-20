 Jan 7th Notes


Review of Bootstrap-
![[Pasted image 20250107183756.png]]
![[Pasted image 20250107183845.png]]

footer-
use span
![[Pasted image 20250107184929.png]]
you can add java script to make the year change as time goes on. 

refresher on how to center your cards using d flex:
![[Pasted image 20250107185100.png]]

Array- a way to make a list of things.
you can use const on arrays 

(document.write is always going to put the java script last on the page.)
the script tag is on the bottom of the page. 
![[Pasted image 20250107185715.png]]
you can maniplate it but there is a better way. this doesnt look right but it is proper syntax.

![[Pasted image 20250107190157.png]]
you can . to see methods for strings
each data type has different methods with .


for loops:
 means for each item
![[Pasted image 20250107190904.png]]
review jan 6 presentation for further explanation of this

-for each loop
![[Pasted image 20250107191821.png]]

unshift is a bully. it pushes everything else. you only want to use this if it is a small array like 12 months in a year or 30 days in a month. if it has massive data it will slow down the comp. to complete the command. 

pop removes an element and is better than shift bc it isnt shifting all of your elements. push and pop are alot better to use. pop will only remove the end element of an array. if you want to remove and element in the middle you will need to use splice or slice.....mdm has good references on how to use it. 

push
pop
shift
unshift.
slice 
splice

slice keeps a copy of the data but splice will remove it not allowing you to do back to it. splice also does shift your elements. try not to use this is the middle bc it can get complicated. 


***Array methods on youtube. 
Lewis highly recommends to watch these. 
*Reduce is very hard to understand but it does a lot. 
The common use for it is to add up numbers. but it does so much more and good to use. ***



-Objects
similar to arrays(lists)
instead of using indexing though you use key value pairs.
you can even create a function inside of an object to give it functionality. 
instead of square brackets you use curley brackets. 
-most important thing to know in javascript. could get hired based on knowledge of objects. 
![[Pasted image 20250107195030.png]]
contains arrays etc it can get complex

j son
XML looks like HTML(but it uses tags to nest)
but in web development you will most likely see json though.


-HOW to add data to other parts of your website.
Instead of it being added to the bottom of your document. 

The solution:
DOM manipulation
![[Pasted image 20250107195910.png]]

Date.NOW()
Date.getYear()

Epoch time is developer time. 
there are methods your can use to return numbers or year etc.
![[Pasted image 20250107200358.png]]
one of the hardest problems to solve is dates esp. if you have users in different time zones.  Local time vs epoch time vs global like time zone(zulu time which is the time zone in England at 0)

-Updating card information:
![[Pasted image 20250107200843.png]]
then change innerText. with inner.HTML
using the h5 element. 
![[Pasted image 20250107201000.png]]
this is called drilling into an object
you may find that you are looping and you may need to use map

-changing the text on the card
![[Pasted image 20250107201302.png]]

this one is more simple:
![[Pasted image 20250107201333.png]]

![[Pasted image 20250107201408.png]]
![[Pasted image 20250107201438.png]]

if you dont want it in a varaible you can add it to the end
![[Pasted image 20250107201515.png]]

this is how to make it a variable and makes it easier to read
![[Pasted image 20250107201545.png]]





homework for lab
how to get the author
![[Pasted image 20250107202138.png]]
 or you can put all your html into a string temperal literal with an id and and use $ signs and make it variable with let
 ![[Pasted image 20250107202837.png]]
 there are many ways to solve this lab. 
to be a good developer means you can solve problems. 

