December 5th Notes
***MAKE SURE YOU STUDY FORMS ON THE WEEKENDS***

forms:
grab the link and script in bootstrap, (link goes in the head and script goes right above footer)
(but you can put multiple scripts together)
header goes in the body**** with nav bar in header
aside element-means its not related to the main content. you can use it like a div or section or article

main goes in the body but under the head****
in gethub
overview 
form
***review the type of forms

accessibily**** on gethub
will make you a better developer than others ***make time to be good at this as freelancer

form disability is good to know too.
forms are something employers will ask you about

the value is what gets sent to the server and process the content is not being sent to the server. the value doesnt have to match content.

research validation page. 
it has javascript that you can use for you form by copy and past into a script file or script element.
**validation if need a validated input you copy it and make a script element and inside the script you paste it. what is does it give you feedback that your form works.
you can customize by using css (style) to change it. 

to start from beginning. go to forms and layout. copy the form grid.
*you may have to adjust the form example part in the code if you copy and paste straight from bootstrap*
*you can also change the background color by adding a class to the body* 
-on main do a class ="w-50" so it doesnt spread across the whole page. also m-auto and margin top 
-then go in and change the placeholder attribute to say what you want it to say. like "address goes here"
(you cant use a placeholder as a label) so  you need the label element for it to be nested in. 

changing the width on the form could cause problems of sizing on different size screens. you want it to say w-100 w-lg-50 to tell it if you are on a large screen go to 100 width but a up to lg only go to 50.
then add m-auto if you have something that is set to w-50.
mt-5 is margin top to move it down a little bit. 

md- stands for medium screeens. 
row gap col give spacing between columns. it gives it some gutter. 
 ***if that isnt changing your form the way you want you can always use css (style)

change after the = to say this....
unput type="text"
label for="inputname"

you can also go in on the form to make it ask for the middle name. you can change minlength or max length="2" if you want it the user to only be able to put so many letters. 
insert this under input="type" 
if you type input and tab on vs code they have many options for input="type"

options to play with
you can also use label="for"
name="date"
id=""

there are calendars available also

color picker.... helps you see the pixels to see the rgb values

in gut you can browse form control-to find textarea
in the code in your form put  div with a class of "col-3"

to add more text areas to this using code from git
<label class=form label mt-9 OR take that out and do mt-50px but try not to use that one if you need to move more than 5- 10 px.
	   write conten that says "event type"
	   input type="txt class="form control"


OPTIONS:
	<option selected add disabled selected>Choose.. </option>
	<option>Marathon</option>
	<option>1/2 Marathon</option
	<option>5k</option>
***when you add disabled it makes it so the user cant go back and must choose. 
										if it doest work you can always use javascript. 
	
