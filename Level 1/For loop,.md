Janurary 8th Notes

+=
keeps your other code on the page. use this to make sure it keeps your current HTML and adds to it!


basic example of for loop
![[Pasted image 20250108190858.png]]

control F will help you find elements in your code


-How to solve with .foreach
![[Pasted image 20250108192912.png]]
this will intiate the loop. but we just cant see it. 

.foreach is a function that is built into an array. created by a developer to loop over.
this is saying the same thing but you dont have to write function
![[Pasted image 20250108193301.png]]
.foreach is more modern but it doesnt have access to i and performance wise .foreach is significantly slower. so dont use it if you have super longer data like millions of users. 

=> this declares the function so you dont write function. 
![[Pasted image 20250108193547.png]]

developers wanted to be more modern and didnt want to write function so they said use an =>

Examples of when to use while loops:
while loop
while we are still on the page
while the user is on this page
while this is true

Examples of when to use to for loops:
iterating of an arrays. these items are "for" .....


-Objects:
having a key value pair syntax is #1 way to handle data. Rather than assigning a variable like let = 
-and you can add any data into object. 
![[Pasted image 20250108200707.png]]
you just need to use the index notation to access data in the object. 

*you can drop a card into the javascript*
![[Pasted image 20250108200841.png]]
and dont forget to include the alt text. and you can use a placeholder for the image temporarily. 
then add dollar signs. and get the info from your object. index indotation
![[Pasted image 20250108200935.png]]
then add your inner.html element AND ALSO YOUR GET ELEMENTBY ID WITH A VARIABLE
LET DEMO = DOCUMENT.GETELEMENTBYID()
![[Pasted image 20250108201036.png]]
if you have a ul on html page remember to wrap your li
(he changed the div to an li)
![[Pasted image 20250108201149.png]]

how to add the image:
![[Pasted image 20250108201415.png]]

use your back tiks then inject your html into java script.
![[Pasted image 20250108201533.png]]


-another way to add a card.
is to insert it hard coded into your html. 
but the problem with that is if there are a million users. you dont know how many cards you need to make so you use a loop. to say if user does this show this if not then dont go any further. 

HOW TO ACCESS POST ARRAY EACH INDIVIDUALLY......
![[Pasted image 20250108202015.png]]

COPIED THE CARD INTO A FOR LOOP. AND ADDED i 
also added ![[Pasted image 20250108202113.png]]
with a plus +=

HOMEWORK:
TOTAL OF 8 CARDS....
USE SECTIONS FOR EACH BULLET.
TO ADD POSTS USE .PUSH


