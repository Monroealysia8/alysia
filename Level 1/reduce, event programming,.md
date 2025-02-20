January 13th Notes

REPEAT LABS TO MAKE SURE YOU UNDERSTAND.

![[Pasted image 20250113184733.png]]
-it adds the numbers against the sum of the first calculation. for junior web developers job interviews!!!very common to come across this!
(used for calculation)
memorize this syntax.....will help you solve the problem . understanding the logic behind it will come.
-mdm is a great way to look up the documentation. 

![[Pasted image 20250113191103.png]]
you can styles like margin in your javascript this way using string template literals. 

console.error
console.table


-data coming in from API's
starwars api-
SWAPI
![[Pasted image 20250113191747.png]]

-REDUCE
(knowing this could land me a job)
using it to calculate grades:
in the ()
it needs another function....a callback function. =>
and you can add it with no name
lambda- the arrow function and annoynmous function
=>
or function()
![[Pasted image 20250113193045.png]]
it needs 2 parameters. for a way to keep track and ....
acc accumulator is also called running total
the first parameter is the running total. or "accumulator"
and it is set to 0 by default
the second parameter is the iterator or "currentvalue"

![[Pasted image 20250113193340.png]]

this is how it looks under the hood not using reduce. 
![[Pasted image 20250113193754.png]]
but reduces better bc you can pass it all kinds of parameters. and bc the for isnt reusable. 

how to get the average-
![[Pasted image 20250113193633.png]]

total screen:
![[Pasted image 20250113195341.png]]




-Event programming

               using a form.
create a form element. 
![[Pasted image 20250113195427.png]]
you need a label if doing a form***
![[Pasted image 20250113195527.png]]
then nest input fields....

to get data you need a button-
![[Pasted image 20250113195724.png]]
 he added a second input type for text
 ![[Pasted image 20250113195825.png]]
 
you could use label for=
but we arent using it in this example

(action attribute on a form is where we go for input) you can remove it for this front end example.

use document.getElementbyId("")

and then add an event
for this example we use submit
step 1 add a form to a variable then add your event listener
![[Pasted image 20250113200216.png]]

![[Pasted image 20250113200205.png]]
add another paramenter
![[Pasted image 20250113200305.png]]
most developers Call it e for event![[Pasted image 20250113200516.png]]


you can create your own dashboards that will bring you to a place on the web after clicking in the text and submit
default behavior of submission is to refresh the page.
![[Pasted image 20250113200737.png]]
this will prevent your page from refreshing

*different events have different behaviors. for example submit will refresh your page*

***remember this because you will prob need to add it when using submit*** ***when it doubt use event.prevent anyways bc its a great tool for all web pages. 
-and you can put it anywhere on the page and it will work

eventListener its different than click bc it puts it in a form. giving you more access for lots of input type text to check for multiple submissions you want to use event.Listener

-use console.log an event  and inspect. as you go to check to find elements (elements are found in target)

-MORE things your can do with this....
can add color....![[Pasted image 20250113201844.png]]
![[Pasted image 20250113201935.png]]
then render it to html file. (he doesnt want us using document.write anymore. 
use document.getElementbyId)




TO DO...CATCH UP ON VIDEO ON DEV TOOLS AND PRACTISE FUNCTIONS!!!!!!!!!!!!!!!!!!!!!!!!!!!

make an array
reduce 
out put it
create form
output text to an h1
after submitting
