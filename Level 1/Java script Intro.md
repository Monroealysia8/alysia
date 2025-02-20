December 16th Notes

Java-script is what makes your websites dynamic!!!

***to inbed directly into html***
*you can write java inside of a script tag*
use alert()

another way:
***add boilerplate***
script
let body = document.querySelector("body");
document.body.style.backgroundColor = "blue";
script


' is a single quote'
"double quote"



***Data Types:***
**Strings-** or string literals
they are just text. inside of single or double quotes. even empty space in between quotes is a valid string. with out the space in between it would be an empty string with the value of 0.
![[Pasted image 20241216192026.png]]
apostophes-
![[Pasted image 20241216192049.png]]
these can cause errors so you will need to add quotations. single or double

string template literal-
they call it template bc it building a template for your string
backticks above the back key..they allow you to format lines. you could eve write html inside of your back ticks.

**Number-**
addition, subtraction, decimals...*java script uses the order of operations*
PEMDAS
so you may need to add brackets or parathensis when computing if you dont want the order of operations order to happen in the code. 

*you can not do expressions on the left side of an operator. 
![[Pasted image 20241216191808.png]]


Boolean-
it will give you either true or false.
![[Pasted image 20241216193633.png]]
when you read this out loud. you need to make sure you say it is STRICTLY EQUALS.
NOT EQUALS

<=   >= 
is the proper way to write it
it will throw an error if you write 
<== with equals signs





Console:
you can write code directly into it to check your code.

Naming convention
index.js
he prefers script.js

script src="script.js script

and src is imbedding a link(not a link without src) ?? review in



***at the top of every single java script you will type***!!!!!!
"use strict";

*he will take off points if you dont add "use strict"*

this means it is newest version and will help you with typos. bugs, etc.

type script- is a subset of java script.
it changes the syntax and makes it more strict. once we learn java script then we will learn this. 

data types is a primitive value. any time you will exchange data you need to understand what kind you are using. 

*if you put numbers inside of quotes they are not numbers anymore they are considered strings*

Functions:
alert(it will make a pop up like prompt)
called a blocking function

document.write 
is a function that lives within in the html...but it does put into raw html. so making it larger will need to add to it so it takes longer.(isnt used that often) and it could possibly delete your initial dom

*prettier auto adds your semicolons*


Strings:
what happens if you add two strings together? 
("5" + "5")
 will make 55 bc it sees them as strings with the quotations instead of numbers to be added.

Concatenation:
the process of adding two strings together
(for example if you had a really long section and need them both to be displayed to page
or if you add two usernames. adding them together) (not adding with numbers)
![[Pasted image 20241216193302.png]]
it doesn't know to add spaces to you can add a space to the end or
![[Pasted image 20241216193340.png]]
another way to write it is it long
![[Pasted image 20241216193412.png]]

*try to think what is the final value of the last expression*
.... to have an idea of what it will look like on the page


LET
use LET and then add any kind of data
(always use let for right now)

CONST
means constant
it is a constant value and you can still do math with this. 
( a good way to not override something)
he will add it to the front of variables)
![[Pasted image 20241216201921.png]]
USE FOR THINGS THAT ARE STATIC THAT WILL NEVER CHANGE FOR THE USER.

another way to declare a variable is Var.
DO NOT EVER USE THIS!!!! IT IS DEPRECATED!!! if you ever see documentation with Var replace it with LET

Camel lettering always starts with a lower case letter. then add caps for first letter of next word.

Typeof:
you can add typeof and it will tell you what kind of data type it is...like string or number, boolean, null, etc.
![[Pasted image 20241216195808.png]]

Null-
it means empty
but it is a valid data type
( you might use this on a form for cell phone but if you dont have one it will be null)


myNum++ adds 1
![[Pasted image 20241216203331.png]]


A cool way to use userinput.

![[Pasted image 20241216203424.png]]
see if you can make those two strings into an email for practice in break out rooms. maybe add another string.

Example of getting user input.
turn off your go live while working with prompt and alert
let color = prompt("Pick a color)
![[Pasted image 20241216203933.png]]
no hypens are allowed on the left side of an equal sign. it means subtract. use camel casing when words are next to each other in styles etc.
 -anytime you see dots it means its an object in java script. 


console.log(window)
it is the dom or browser that will pop up.

BREAK OUT ROOMS:
![[Pasted image 20241216204455.png]]





