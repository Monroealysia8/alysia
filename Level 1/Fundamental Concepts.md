November 25th Notes-Monday

Code spaces is basically a computer..that you are remotely connecting to....to let someone else come in a look over your comp.
if you start to run out of space on your computer with vs code you can use codespaces. You do not have to download hithub etc. if using codespaces. its already linked. it has its own ram and GB. so when you save your work it as if you are on its own computer and will need to delete files like you would like folders on your computer.

Commands & more HTML info.
The URL is the address of a web page, like: **https://www.w3schools.com.**


****html 
figma-drawing tools (will need it for week4)
use mdm documentation to find all the elements to use in HTML(semantic elements)
meaning the element  itself describes the content....
non-semantic element includes the <div> for  layout element..
<span> this one separates things on the line
<br> is one also
HTML(NOUNS)defines
CSS (ADJECTIVES)
JAVASCIPT(VERBS) gives interactivity-basically powers the internet.

****html structure
think of html as the browser information or the root..bc it goes at the bottom of everything
content=""        this optimizes your webpages..makes it show up better on search engines
<body> is where all your content goes for your webpage
****<section></sections>  for news articles or images from news articles....usually has more elements in side of it....think of it like the <body> it needs elements...for example you can give it a <h2> for that section.
press control key <!--  --> for notes just for coders  to use for organizing ( control + forward slash) to use it.....
you can temporarily use control forwards slash to hide code if you want to use it later it will make it gray. Can be used in all languages.
to remove it press it control forward slash again and it removes the content from the notes
![[Pasted image 20241125190158.png]]

employors may ask...do you do documentation...this is what they are asking about....

<article>also has elements inside of it
<h2> <P> if you want to have an article wrapping your page then you can..you get to do it the way you want. there is flexiblity with semantic elements

dont do this though bc a heading tag is for a heading tag
<h2><p> hello</p><h2>

******[NESTED ELEMENTS]
<li> are considered the same thing as a <p> element so you dont have to use the <p> tag when you use it
![[Pasted image 20241125191613.png]]

****nesting is the backbone to css to build a webpage...

****<span>****** is a non semantic element that helps you manipulate things...allows me to use attributes in css
example:
<span style ="color: blue;">World!</span>

example:
<body>
<h1>hello<span>World!</span></h1>
</body>

examples:
<nav>
<a href="index.html">Home</a>
<a href="aboutus.html">About Us</a>
</nav>

TRY USING THIS:
body style=(press tab to pull up options) for example background color

to make bullet points in a list:
<ol>
<li>First items</li>
<li>second items<li>
</ol>

Hyperlink:
create folder first then..create an html file calles aboutus.html first the you create a hyperlink to give the browser information where to locate it
< a href="somewhere/aboutus.html">About Us</a>

(a file with capital letters in it are rare and it means that it has some very important content in it. for now only use lower case letters in)

***commit messages
when you need to delete a file on vs code you need to press the commit button witha message that you deleted it. this is a great way to figure out your history when working on a webpage. important for seeing what i have done on my page.
for example ...first commit second commit deleted aboutus.file ect. 
then when you are ready to send it to github to click publish.

cheat sheet of all elements on slack

****TABLE ELEMENT****
HOW NESTED THINGS CAN LOOK USING TABLE
you can type <table> then tab and it will pull up options from mdm

example:
<table> type style= and then options come up
<captions> and <thead> would be siblings....
he never memorizes this stuff he uses mdm if he wants a table.
<tr> has nested <th> in it
***terminology....child and siblings...
 the T is because you are using <table>
 container is another word for container... usually meaning parent...
 ![[Pasted image 20241125200550.png]]

using <ul>
you can type<li> and type 5 to make 5 <li>'s

 ****an anchor tag in a <li> is not another child its just content****

*** we use <li> for screen reader purposes

****for styling you can use FLEX to make it horizontal

(on real applications he hardly ever uses tables on html bc they are very hard and hardly ever asked of him)


******ATTRIBUTES*****
to add an attribute to an element
attributes are ALL PURPLE
use ID to add attributes
<h1 id="heading-1>Attributes</h1>
		<section class="part1">
<section class="part1">???????????
					
	![[Pasted image 20241125202025.png]]	  

****HREF is also an attribute
<a href="index.html">Google</a>
				

****IMAGES
<img id="" class="" width="" height="" src="" alt="" srcset=""
									  
![[Pasted image 20241125202414.png]]

<img src="" is either a file or an external link
		   SPLASH IS A GREAT PLACE TO FIND IMAGES
		   YOU CAN RIGHT CLICK AND THEN CLICK COPY IMAGE ADDRESS TO ADD IT TO YOUR WEBPAGE
****a cool way to resize image is to adjust he size in the URL instead of adding width="" or height=""


****alt="person in all black sitting on motorcycle
[[Pasted image 20241125203040.png]]
add this to your images you down load....it helps with screen reading.... if you dont add it will read off for people with disabilities etc. add it alt=""> at the ALT at the very end of the URL of the image. 




## How to View HTML Source

Have you ever seen a Web page and wondered "Hey! How did they do that?"

### View HTML Source Code:

Click CTRL + U in an HTML page, or right-click on the page and select "View Page Source". This will open a new tab containing the HTML source code of the page.

### Inspect an HTML Element:

Right-click on an element (or a blank area), and choose "Inspect" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

---

	There are two ways to specify the URL in the `src` attribute:

**1. Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

**Notes:** External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

**2. Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

**Tip:** It is almost always best to use relative URLs. They will not break if you change domain.

## The title Attribute

The `title` attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

### Example

<p title="I'm a tooltip">This is a paragraph.</p>

## Single or Double Quotes?

Double quotes around attribute values are the most common in HTML, but single quotes can also be used.

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

<p title='John "ShotGun" Nelson'>

Or vice versa:

<p title="John 'ShotGun' Nelson">

**Note:** A link does not have to be text. A link can be an image or any other HTML element!


## HTML Links - Use an Image as a Link

To use an image as a link, just put the `<img>` tag inside the `<a>` tag:

### Example

<a href="default.asp">  
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">  
</a>

## Link to an Email Address

Use `mailto:` inside the `href` attribute to create a link that opens the user's email program (to let them send a new email):

### Example

<a href="mailto:someone@example.com">Send email</a>## Button as a Link

To use an HTML button as a link, you have to add some JavaScript code.

JavaScript allows you to specify what happens at certain events, such as a click of a button:

### Example

<button onclick="document.location='default.asp'">HTML Tutorial</button>

***how to check for bugs in my coding
go to W3C markup validation service. click the file tab if its not on the web yet. open my code through my local folder and upload for it to check.



[margins and padding]
Although they both add spacing around them, margins and paddings are different.

The padding adds space between the content and the border, while the margin adds space between the border and other elements.
example: of how to style a nav bar
a{  

  background-color: chartreuse;

  color: blue;

  font-size: 20px;

  padding: 10px;

  margin: 40px;

  border-radius: 10px;

  display: block;

}

to make a border around each a tag use
 border: solid 2px gray;