lab 3. Homework can be a portfolio for any of your choosing. photography portfolio etc.

you may need to bring in multiple rows or not for your grid. if you put the grid on container it will be responsive automatically

the carasel needs three slides and 3 images. 

|     |     |
| --- | --- |
|     |     |


card part you dont need actual 3 projects. just how to showcase those skills of making a card. make sure you grab the card from bootstrap that has image title and description.

you can use customze width but try to use bootstrap.
a card component comes with a styling of 18 rem. so you need to make a custom styling for width on this one. 

this week we want to make sure everything looks professional by this week!

learn from your feedback that is giving ***

||||||||||||||||||||||||||||||||||||||||||
December 4th Notes
 for lab*** on the lab instructions... you dont have to make it link to anything.. you can just put it into a notes section. 

fork takes code from github to clone it and get github to change modify  it. license agreements will prevent you from changing their logos, or adding malicious. sometimes you will see something that says dont fork this. if you need us to change something they want to make the change not you. 
you can go into bootstrap and tell them this is wrong and if you want to contribute you can show them your code that you think it correct.

Notes: upload your links(2) add l script to script tag and the other is the link in the head. it doesnt matter where in the head it is placed. 

bootstrap is so good because of the library of components!

Nav bar: are fluid in there width so they will take up the full space. responsing and collapsings: a hamburger .navbar-expand {-sm}|-md|-lg|-xl| hamburger is if you use a smaller screen it will collapse.

***navbar toggler for hamburger.

take the some to read the nav info in bootstrap.
import the nav bar in your header. and dont forget to add notes stating the beginning and ending of your nav bar code thats imported. 

disabled on nav-you can put admin or the users name. if something is out of stock on a website you can use the disabled. he usually doesnt use diable he just makes it dissapear unless you want it to be seen that its not accessible. the choice is yours to use disable. 

if you want to add an item inside of a drop down you take the element like li and copy n paste it with new text to add to the drop down. 
 *** you can link you nav bar link to other parts of the webpage. by adding an id. 


if you see something that says aria. try not to mess with it. its made by default.

how to add an id to link to defferent sections or to use on your nav bar to link to sections on the nav bar that refer to things in the text part of a website. 
you can section= id to ANY element with < a href="#banana">projects  <a>

this is in project go to time 7:05 12/4/ class to review lecture. 

sections part of the page: create sections to make it easer for you as you code. 

you want the navbar to say the name of your company. photography llc |Alysia Monroe

****adding h1 to navbar:****
some developers will add the h1 to nav bar in this place too. and then use the class on h1 to be a smaller.
h1 class = "h6"


***Carousel***
you can add it h1 in the body or main in section
to understand how it works...
you have to have an image. 

its should not grow and shrink between each image. if you can put this into your site it makes you a much better developer in  bootstrap.

example:
in main add a section for notes for the beginning and end of carousel code you are about to import. (this helps you find your code)

press control s to prettier it. everytime you add code!!!!!

you want to use the elements already there but you can add more or more buttons. some dont have lines which are limitations. your choice. some have text on it. to add just image you add an image with only a white back ground and add your text for the text to scroll without an image. 

go to unsplash to get your images. drop them into the src...delete the 3 dots in src. 

you can do a carousel to slide all your projects*****

sometimes you need to make the image smaller. 

class="vw-100"
to make image smaller. 
vw means the entire of your screen. 
sometimes you need to go to inspect on devtools to see why the image wont move. 
(or)
you can go to css for sizing. do an inline or create a style sheet. 
under section or div to style="100 with px
or try using object fit in bootstrap -w-100 h-100 object-fit-cover with the image and everything inside of div

***if you need it to be done in css
img{
width:100%
height:100%
object-fit: cover;
}

**the parent of the div is where you put the widthand height for these

***on styling page or do inline style on the img 

use
.img-wrapper{
height: 300px 
width: 100vw
}
and then add it to the 
div style="height" :300px; width: 100vw class= "caraousel-item"
img
src=
class=
alt=


(you can always add an extra section to add class to something that you want to have a style but it already has a class on it.)




if you dont have the class w 100 h100 object fit:cover it will break the carasoul.

unplash can be very hard bc of there image sizing..dont use it OR use screenshot. 
Easier way is:
screen shot: by opening a new window.
create a file somethin.md  to put img in so i dont have to mess with sizing. 
there i can use paint and crop it the exact image size i was . 
then add the img.png to your src in the images code. 

look up absolute
![[Pasted image 20241204193845.png]]

***this is really tricky for a while and make sure you ask for help on images

you can paste or drag your png screenshot. 


how to fix your prettier alerts***
it will tell you what line at the top of the terminal. go to that line and it will tell you what element is wrong. 

***to move a line ..go to the line to move it
hold alt and press up*****
or down if you want it to go down


***Acordian Component***
he uses this quite a bit. you can manipulate to be something other than an accordian.
-it grows and shrinks a div

he grabs the top one to follow along with him..
put it in a section with a code comment for yours notes. paste it into div. then formate ctrl s
its very simple to use but you must have java script for it to work. 

you can change the size of it.....to match your image but grabbing with width from the carasoul and adding it as style under the top section of your accordian. 

remember to use d.flex on elements like main or section etc to make it a 2 column design where it is right beside each other. and the alternate down the page from text and images. you can add shadow by using absolute positioning. so the text can show over it. will be taught more shadowing later in class. 

you can add span around a word of text in a paragraph to add a div 
lorem ipsuym <span id="banana"> span loren ipsum. 

footer:
footer p copyright 2024 &copy; Lewis Benson footer
**you can add a nav to your footer with a href

main goes above footer.
vh-100 
sets the image to the height of the screen.
*******if you want the footer at the bottom****
do this
put this on the<body class="
 vh-100 d-flex flex-column justify-content-between"*******


how to add a grid and put a card in it************************
(grid- use the first one under layout grid.
put it in section) and div class. inside of each column        
					 div class ="col"
					 is where the card goes. add notes

-grid uses flex-box
div class is set to "row"
	you can add back ground color 
	by class="bg primary">
	each row is worth 4 units of space.
	if you add another the units of row will be 3. bc you are only allowed 12 units to it breaks it down depending on how many col you add. 
	to make a new row copy the div that has the whole row you want and paste to make as many as you want as long as it inside the container at the top where the grid col begins. highlight everything UNDER the container div and paste under it. with a new line. make sure not to grab the container. 
	the grid system is really good at creating your lay out. you can add in the div in your grid to add the carasoul to one of the grid.
	


****divs OR sections***
-which is best to use??
	you can use divs and sections interchangable. best practice!!! divs are for 
	if you use a section you should make sure you use atleast 2 i otherwise use div
	sections are a better way to break up things within the footer or whatever major element on your code. sections even pause for the screenreader to allow them to understand this is a new section. use that thought as you use sections. 
-developer really havent figured out what the rules are because they are so new. the industry can shift and always changing so we need to stay up to date on what developers are learning that is new. 

in navbar add #contant as a drop down
to make it jump to the footer where you code 
footer id="contact"
so it will jump down using a bookmark

lab requirements: it requires styling
use class=mt-5 to push things apart in the section tag for your cards and other places.

HOW TO LINK THEMES
THERE IS A DIFFERENT LINK TO ADD BOOTSTRAP. SO REMOVE THE NORMAL LINK AND GOOGLE. BOOTSWATCH.COM
scroll all the way down to the themes.
pick one. click the drop down min.css version
add it to your bootstrap.min.css page. 
then link it to your document. 
link rel="stylesheet" href="bootstrap.min.css

and link it on all of the pages you have in your website. 

*****make sure you put bootswatch link above your style link in the head tag.
otherwise which ever one is last will win. 

check the versions you use. when looking for themes and you may have to change the colors around if it doesnt work

OR
css
coolors theme
explore trending pallets
create class with what ever name you want. click on the color pallet yo want go to style sheet
.bg-banna {
background-color: paste the color
}

use a.i for color also...
css  must be linked under bootstrap.

add the link rel stylesheet that has your name you made on css  and add it with . in the section or div as  a class in the body or where ever you want it.

if you make a portfolio make it long..bc people love to scroll. 

breakout rooms work on labs. 