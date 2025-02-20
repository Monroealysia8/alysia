December 2nd Notes

Prettier:
control S to format. click this after entering content while working

internal styling:
add the style tag to your heading and add all your styling to that tag. (use this when using a single file.)
with multipage websites use external styling by making a style.css sheet.

inline styling:
its for if you need to style one thing real quick for one thing
you would put the style have the element once in the body elements.

dry:
avoid using the same code more than twice. 



DIV will add a line break
SPAN does not add a line break

div is for layout and should be used last with semantic elements. 

when to use a div:
ul{
diplay:flex
justify-content:space between
list-style-none;
}

(space-between spreads all the children evenly apart)

ul
div
li 
li
div
li
ul

puts a space between the divs

here you can add an id="links.left"
then in css 
#links-left so only that one div is selected to make the flex work on all the li if there is div in the code.

example of flex:
display: flex;
justify-content: space-between;

***the only time justify content: space between only works with display:flex;

(never use float it is considered bad code..has been degragaded)

create a reset.css
remove all default browser settings like that margins ect.

import the reset page online. 
link stylesheet and reset

class...you use the . on css

id has specifity over class so it will show up over
id. it will always override id. if you move your curser it will show
0,0,1 means 1
0,1,0 means 10

in line styling will also overriding classes. 
h1 style=

on stylesheet if you type !important it will also override everything. but dont use it bc it means infinity. avoid it when you need to override imported information from another site.  

to increase specifity
main p. section{
background-color: pink
}

body > main > p section{
background-color: pink
}

(if there are several selectors or children you only need to use the last two)

do the dino quiz he sent it teaches all the ways of css like the notes above


utility classes: 
you have to basically rewrite the css language.
..d-flex {
display: flex;
}

add class to semantic elemants. 
(only one style per class name)
you create a class in style sheet with a . and then add it to your pages. 
a library has these already made for me to create a class. you will need this bootstrap. 

just by creating your utility classes on stylesheet you can then apply it anywhere you need on the page. you dont need multipe styling.

you can create something called .button on style sheet and then had all that you want the buttons to do on all the pages that have button with the colors and spaceing etc. you want on all the buttons. all you have to do is add style="" behind the element in your content on the pages. 





***BOOTSTRAP****
is css but you dont have to actually write any css. 

google getbootstrap.com
include via CDN
cdn is mina fide code is code on one line. one big massive file makes up bootstrap.

copy this link and add it to your index.html as a link in head (you dont need to create a reset.css with bootstrap bc its already built in)

the second link below the first one gives bootstrap functionality so also inlcude this in your website. if you dont need functionaly you can always delete it later. wont know until level 3.
its ascript**** has to go in the body and it MUST GO IN LAST. SCRIPT ALWAYS GOES LAST!!!!

what this does it if you switch to a mobile device it will allow you to get things like nav bars that have hamburger menus ect. that adds functionality to your page.

you dont need to install a package manager yet 
 go to docs. page to grab boiler plate to put in your code. there are other scripts to add popovers from this site. 
on the left the most poular you will go to is 
components:::
it has nav bars, cards, etc. you copy it to clip board and then good to go. format and view it. you can make websites really quickly by using these compenents. then go in and edit the content that you want on your page in the copied code. 

if you are having trouble finding something. right click on code and dev tools show up on right. click copy then copy selctor. go back to code to trace where things are. another way is right click on the preview of the website. right click and it will highlight to code on the right. right click it and it will highlight the selector or type into search bar and it will pull up on code highlighted. any time you see a . its a class. if it doesnt have dot its an element. nested elements like the ul you need to be careful when viewing. it you can use collapse to help you see it to edit code. 

you can search other premade compentents of bootstrap and copy. 

components:
you can get buttons, cards, nav bars, 

to use a button you add a class on to an element like p. class="btn" 
when making class names isnt about what the element its more about what it looks like so use what color button it says inthe code and thenname your class that

you can add a button to an a tag. after the url type class="btn-primary">sign up! closing a tag
(anytime yout want to go some where use the a tag right now)

variants are buttons that are already styled. 

utilites:
background colors: opaque

to add it type in     body class="bg-primary">
and you can change up the colors just by changing up the word on the code as your viewing the preview

to add the color of text type in the class behind the first color type text-white

****with bootstrap you use div


***you dont really need a .css page when using bootstrap except if you have a card

where you will need to make your own utliity class. 
a rem is a unit or measurement
.w-15{}
width: 15rem;
}

html{
font-size: 10px:
}

:root{
fonst-size: 10px
}

(all of these are rem's they are root default sizes)

1 rem is 10 px

so once your style sheet is made with rem then add style to div you want the card in. 

explore your docs on the left in bootstrap for break out rooms.