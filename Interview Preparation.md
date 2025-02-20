![[Pasted image 20241210003636.png]]
Note: the 10 problem solving strategies are:

- Wishful thinking
- Try Something!
- Draw a Picture
- Make Up Numbers
- Try a Simpler Problem
- Work Systematically
- Use Manipulatives to Help You Investigate
- Look for and Explain Patterns
- Find the Math, Remove the Context
- Check Your Assumptions

There is a general programming term “closure”, that developers generally should know.

A [closure](https://en.wikipedia.org/wiki/Closure_(computer_programming)) is a function that remembers its outer variables and can access them. In some languages, that’s not possible, or a function should be written in a special way to make it happen. But as explained above, in JavaScript, all functions are naturally closures (there is only one exception, to be covered in [The "new Function" syntax](https://javascript.info/new-function)).

That is: they automatically remember where they were created using a hidden `[[Environment]]` property, and then their code can access outer variables.

When on an interview, a frontend developer gets a question about “what’s a closure?”, a valid answer would be a definition of the closure and an explanation that all functions in JavaScript are closures, and maybe a few more words about technical details: the `[[Environment]]` property and how Lexical Environments work.

January 14th Notes
-call back functions
(can be confuseing)
.for each makes a for loop
![[Pasted image 20250114184301.png]]
***if you can memorize this syntax you will be ahead!!!!!!!!! will be interviews*************

.for each is going to return undefined!!!!!
all of the logic is inside the {}
itjust does some stuff whilelooping

so add....![[Pasted image 20250114184734.png]]
and it is very important to declare your variable above the function bc it only exists inside of the curley brackets.
another reason is its a loop. 

STUDY THIS!!!!!


-.map
-another call back function
![[Pasted image 20250114185518.png]]
its doe the dame thing as .foreach
dont use it for counting numbers though
use it for assigning a variable
![[Pasted image 20250114185607.png]]


.reduce needs a function in the parameter




knowledge of Methods:
january 15th Notes
Adding/Removing Array Methods
![[Pasted image 20250115184916.png]]
list of all those methods:
![[Pasted image 20250115184746.png]]
 *avoid using .unshift on large data because it will crash your site*


A good one to know!
Look up them on MdM
array.prototype.slice()

![[Pasted image 20250115185625.png]]

Reverse a string and changes it into an array:

![[Pasted image 20250115185758.png]]
.split is a string method and splits each word
![[Pasted image 20250115185834.png]]
this reverses a string and makes it into string and splits each character

.join
then you have to change this back to a string
![[Pasted image 20250115190153.png]]

java script - john duckett


google 
...
called spread syntax

![[Pasted image 20250115213237.png]]
then write a message about max rain fall is ![[Pasted image 20250115213320.png]

ask chat gp to generate a javascrpit array of object with lots of numeric data. to practise this .reduce and .maps

do this for functions also!!!!
you can use the sample data to work on adding up things


![[Pasted image 20250115213933.png]]
example of student on how to use the for loop instead of for each

  

// daysWeather.find array method that finds the first match and returns the value

// youtube video it

Books to read up on interview:
Meta Careers

Data structures & Algorithums:
any study on these are helpful for interview
review the fundamentals for now