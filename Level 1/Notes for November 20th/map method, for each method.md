
![[Pasted image 20250116184014.png]]
 to add things up you can use .reduce or for loops etc.
* reduce requires two parameters.
* the first is a function
* the second is what do we want this to start with 5 or 0 or where ever in the array you wan it to start*

-.reduce:
const totalCost = shoppingCart.reduce((runningTotal, item) => {
return runningTotal + item.price * item.quality;
}, 0;

*then use maps to join everything together for table and this is your second parameter for .reduce*

on html
![[Pasted image 20250116185105.png]]
 rewrite these in html then  copy them and inject them in script to use there with back tiks. in the variable 


back ticks string template literals can also take strings
![[Pasted image 20250116185356.png]]
![[Pasted image 20250116185734.png]]
![[Pasted image 20250116185718.png]]
and write total
with out col span in the footer makes things look nice. 

![[Pasted image 20250116185829.png]]

.map method is just another way to do a loop but it returns the value to another array.

.join takes from an array and makes it into a string. 

in dev tools you can add - or join two email addresses but it has to be two. 
you can only join things that are a string
![[Pasted image 20250116190047.png]]


function sum(){

  

}

  

function multiply(a,b){

return a * b;

  

}

console.log (multiply(3,6));

console.log(multiply(2, 4));