December 19th Notes

to directly write java script into html. make a script tag like usual at the bottom with a link to your script.js and then make another script tag above it to add it. 

-Developing work flows:

Using prompt and form-
Event driven programing:
-getting input from form.
*its always a string with user input even with a form*

type myNum. then tab to get different tools

Infer:
it means javascript can figure it out. it can take a guess and figure it out. You can use this to do several things. (console.log supports comma separation)![[Pasted image 20241219185154.png]]
or
![[Pasted image 20241219185446.png]]by using the * 
it is telling the comp that its going to be multiplication and so it knows it is a number. eliminating the need of converting your prompt string. 
to a Number.
(*this does not work with addition though*)

if using addition you can add Number to the prompt.
![[Pasted image 20241219185647.png]]
this is hard to look at so it is usually better to use variables like i have been doing.
![[Pasted image 20241219185730.png]]

-parsInt is another way to conver to a number

adding a plus sign before the variable can convert it to a number also..but it can be hard to read.
![[Pasted image 20241219190246.png]]



Comparison-
if ()
a boolean. 
![[Pasted image 20241219190609.png]]
the only way to use $ is if you are using back tiks and when you are injecting variables. 

Example of syntax of using if statements. Follow this work flow everytime!!
![[Pasted image 20241219190812.png]]
![[Pasted image 20241219190910.png]]
write if
write ()
write curley brackets
![[Pasted image 20241219191140.png]]

-Adding else if
this is going to work exactly like the else statement.
![[Pasted image 20241219191331.png]]
*adding the last else is not a requirement*


Example of when you dont need the else if only need the if
![[Pasted image 20241219191434.png]]
(this would output null...we can fix that with loops.)


-Using functions:
![[Pasted image 20241219191936.png]]



Return does 2 things:
-it ends the execution of your function
-is also takes what ever you return and store it in a variable...like console.log![[Pasted image 20241219192205.png]]
*functions can be anything you want. they describe something. make is bananas if you want instead of login*


Const:
-some developers call const. variables.
-you can use const. as much as want. in fact is is preferred to use.
-dont use this if you want to use it again. it cant be reused. 
![[Pasted image 20241219192555.png]]

let - means you a reassigning it
![[Pasted image 20241219192727.png]]

declaring variables:
adding let above a functions means it is assigned to that function only. and thats allowed

-the difference between const and let. 


Lab 2 review-
you can console.log alert document.write with functions...but better to use the get element to get practise.
when you see the name render than means get the element by id.

to add an id and div 
![[Pasted image 20241219200211.png]]
 then add variables at the top of file
![[Pasted image 20241219200240.png]]
then inside of functions
![[Pasted image 20241219200330.png]]
then copy that into each one.
![[Pasted image 20241219200352.png]]

![[Pasted image 20241219202740.png]]

Additional info for the week:
-How to we get userInput from a form or element. 
comparing the age of two people:
 create a label on index.html
![[Pasted image 20241219200631.png]]
then copy it again
![[Pasted image 20241219200846.png]]
you can had br or div or css flex box to make them appear seperated.
then go to script.
and add it to the bottom.
declare your two age variables with let
![[Pasted image 20241219201230.png]]
add value
-then convert to a number
by adding person1.value

-now how do we get it do all this stuff once the user is done typing?
you add a button!

inside the label add button
![[Pasted image 20241219201713.png]]

then in javascript
add declare another variable with let
![[Pasted image 20241219201726.png]]

and add a function
![[Pasted image 20241219201812.png]]
 and then wrap all the info in the functions to wrap the button in the function![[Pasted image 20241219201951.png]]
 
then to make the button work when you click it..
![[Pasted image 20241219202119.png]]
-addEventfunction has many tools. use tab to scroll through.
all of the events. he used the click event. 



***research the difference between declaring and assigning and reassigning. and when to use const. !!!!!!!!!!!
 research the $ sign 
go to w3schools
click on java script
then read syntax and do the exercise. and variables also.
let const.
operators
data types
functions
Numbers
and brush up on bootstrap
 do this on break!!!!!!!!!!!


