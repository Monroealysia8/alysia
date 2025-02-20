December 3rd Notes

a tool to help finding styles in bootstrap. create a css type it in and let the ai find the name to copy it into to the search bar on bootstrap website to find it so you can copy the code and add it to your website.

**take the time to read the margins and padding in bootstrap

to add a second class under one element by seperating my space 
for padding you add pb-3
px-3
py 4 and more options available

**typography is for text. many developers study this. you should take a class in this bc it makes a website better
. it is the most important part of design. youj can  also use google fonts. there you add it to a cart and hit downloard all or enbedded code*
and then add these into the head of the document or css document. 

use the interesting fonts as your headings 

add:
on body or main class "container">

container is a class in bootstrap that resizes based on your screen size. it will set the width based on your screen size. it will expand and minimize it automatically for you. it is required also for certain elements in bootrap for it to work. it isnt  a label for a container its a way to add some styles of width in pix and other margins etc. 
its main purpose is to make it responsive for all screens including mobile.

in dev tools the top left icon will show you a preview of what your site will look like on smaller screens.

a little advanced explanation...wont need to know this for this class. 
media queries:
they over ride your styles
example:
@media (width < 720px) {
then type your class element with is color you has set
}

you can download themes to help make your website more unique.

nav bar: if it says collapse that means its a hamburger....
expand-lg
is what make it resize to screens

you can copy and paste in to ai to find out what it does if you are looking through bootstrap.
to make sure what it is before you use it or if you want to remove something that you have coped into your code.

GRID SYSTEM:
ROWS & COLUMNS
two urls
grid and css gid

css grid- is something you use in stylesheet kind of flex that helps you do things.

grid-
add place holder then yours cards.
bootstrap has 12 columns that divide the pages up.
in each column in has 4 columns. in each one. 3 times 4 equals 12

sass variables:
 you can paste your grids into the main element if you want. 

(you can add a div section article p p article section div

to add in a column)

gutter is what is the space between the columns. 
you can adjust columns by "col-4" or col-"12" to make the column span a different length.

columns take up to 12 units. so a maximum of 12 units of available space. ...if you say col without a number it will just adjust it depended on the size of other columns. 

another thing is your content may overflow so you can shrink you content. you dont want it to spill over bc it will put it on another line. making a new row by default. 
md-12 will make your columns adjust to smaller or larger screen sizes to keep it from spilling over. 

height: look for sizing. 
on stylesheet. 
to make a custom value
.h-100px[ 
height: 100px;
]
on html make a div.
div class="h-100px hg primary">

as long as you have your css linked under your bootstrap link the css will over ride the bootstrap to be able to use both on one website/

*****
***on style sheet you can move you curser over the . or # it will tell you if you need to write class or style or what element to use on your html file
*****

![[Pasted image 20241203203011.png]]

add sections saying the bottom and top of card to change colors to help you organize it
****colors.co
has color palette colors to copy..
make a # the past the color you chose in code. or just write the number.
chatgpt is really good for choosing colors too. you can type website for coffee shop.
it gives you variables that you can use. you can even type dont use var in chatgpt if you want it the regular way. 

if you use var you need to write var on style sheet. 

you can create a css sheet called colors. css and upload all your colors on your color.css or sass(syntax sugar for style sheets) if you are doing like a 100 page website where it can get a lot.

use ai to generate colors*** and to help you get rid of bugs. you can type fix my syntax error and it will fix it and tells you what needed to be fixed. 


when making cards: find it in bootstrap. 
div container
div row
div column.
you can copy this from grid. 

try:
3 cards in bootstap. for breakout rooms

![[Pasted image 20241203210815.png]]how to make a column and card
 then copy this code and paste a new one of this to make two cards. remove the style attribute. find an image on unsplash for your card.
  
div= col 
under this you add the cards. add your notes on page.

****find and replace**** on the top of the screen is used if you need help changing many things on code at once. copy the code you want changed and enter the code you want it to change to in the bottom search bar. click the button that says replace. and all the edits will be done. !!!!!!!

mt-margin top
mb-margin bottom