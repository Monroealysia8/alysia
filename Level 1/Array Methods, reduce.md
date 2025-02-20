Janurary 14th Notes

Array Methods to help you understand .reduce

its okay to use const for Arrays bc you dont want to over ride your data.

![[Pasted image 20250114183840.png]]
this is better than the square bracket notation...
myArray[2]
because you can attach more on with a.
and can also count backwards with -
![[Pasted image 20250114183950.png]]
you can also put ?![[Pasted image 20250114184010.png]]
your saying if it exists you can call the next method if it doesnt exist if will stop and be undefined.

-call back functions
(can be confuseing)
.for each makes a for loop
![[Pasted image 20250114184301.png]]
***if you can memorize this syntax you will be ahead!!!!!!!!!


-.map
-another call back function
![[Pasted image 20250114185518.png]]
its does the dame thing as .foreach
dont use it for counting numbers though
use it for assigning a variable
![[Pasted image 20250114185607.png]]


*************
![[Pasted image 20250114190107.png]]
.reduce needs functions int the parameter
(you can do alot of cool stuff with .reduce but people done use it bc  no one can see you code. still valuable information for interview)




-Tables
html table review:
![[Pasted image 20250114191051.png]]
you dont put data in the head....for example "bob"

use tables from bootstrap for lab 1
![[Pasted image 20250114191445.png]]
you can add w-5 to make it 50% of the width
![[Pasted image 20250114191551.png]]
![[Pasted image 20250114191608.png]]
in script

![[Pasted image 20250114191812.png]]
use .foreach to loop over each person in the array.
![[Pasted image 20250114191954.png]]
 to build out the heading use an object reference.
 object.entries
 also check mdm for reference to help youit will tell you you need a for loop
![[Pasted image 20250114192252.png]]
to give your name and age....which is the heading of the table
*you can use this when you dont know what the data is coming in for your headings*


    (this is a second way to solve same problem)
-How to create elements manually:
raw nodes actual html elements that live in your java-script memory:
document.createElement
then put it in the DOM
(this is a common way rather than using backtiks bc it allows flexibilty)
if its something small you can use backtiks.
on the lab you can use what ever technique you prefer.
![[Pasted image 20250114195855.png]]
then add a loop
foreach is saying for each person add a tr
![[Pasted image 20250114195944.png]]
then add some innertext
![[Pasted image 20250114200015.png]]
then you need td for name
so you modify the name
![[Pasted image 20250114200103.png]]
then add age
![[Pasted image 20250114200157.png]]
the tr is in gray and it needs to get on the DOM

.appendChild
so we need to append
it puts the child inside of the parent
using appendChild

(an example of what it would like if you were hard coding it)
![[Pasted image 20250114200743.png]]
![[Pasted image 20250114200331.png]]

tr. will give you methods for html
![[Pasted image 20250114200610.png]]






Bonus Info:
For of loop:
![[Pasted image 20250114201152.png]]
it has to be an array


-For in loop:
![[Pasted image 20250114201234.png]]

but he defaults to traditional for loop or .foreach





labs:
you can use foreach instead of for if you want.
you are totaling up numbers. use foreach or for
all assignments needs an index on your home page. create a index on index page to naviagate if having multiple pages. 
*both of these labs must be in by Sunday!!!!! or i cant do the capstone project*
