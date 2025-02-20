November 26 Tuesday Notes


html. boilerplate
<body>
<header>
<nav>
</na
</header>
<main>
</main>
<footer>
</footer>
</body>

****add to EVERY website!!!!!!<header>
<main>
<footer>

Table:
<table>
<thead>
<tr>
	<th> <th>
	<th>
	
<tbody>
		<tr>
	  <td>
	  <td>
	  <td>  

<tfoot>
	<tr>


********use mdm tables so i dont have to remember****
then add or remove as needed

another example on code:
![[Pasted image 20241126190419.png]]

YOU CAN GOOGLE TABLESTYLES.CSS
***read thought the second link is mdm*** it is also in the class chat. 

*you can copy tables and added to your coding* you need to read this to know how to style your table





starting to think like a developer...is using code from others that have solved the problem and modify it.

<td> stands for table data...it represents a column or cell.

<th> does the same thing but it makes the font bold. so this ill be your heading
(you can make an empty heading for a blank space)

[Form]
**Forms** are used to collect data inputted by a user. They can be used as an interface for a web application, for example, or to send data across the web.On their own, forms aren’t usually especially helpful. They tend to be used in conjunction with a programming language to process the information inputted by the user. These scripts take all manner of guises that are largely outside of the remit of this website because they require languages other than HTML and CSS.

The basic tags used in the actual HTML of forms are [`form`](https://www.htmldog.com/references/html/tags/form/), [`input`](https://www.htmldog.com/references/html/tags/input/), [`textarea`](https://www.htmldog.com/references/html/tags/textarea/), [`select`](https://www.htmldog.com/references/html/tags/select/) and [`option`](https://www.htmldog.com/references/html/tags/option/).

[`form`](https://www.htmldog.com/references/html/tags/form/) defines the form and within this tag, if you are using a form for a user to submit information (which we are assuming at this level), an `action` attribute is needed to tell the form where its contents will be sent to.

The `method` attribute tells the form how the data in it is going to be sent and it can have the value `get`, which is default, and latches the form information onto a web address, or `post`, which (essentially) invisibly sends the form’s information.

`get` is used for shorter chunks of non-sensitive information - you might see the information you have submitted in a web site’s search to appear in the web address of its search results page, for example. `post` is used for lengthier, more secure submissions, such as in contact forms.

***there are two ways to use a form***
you can next it...
you can use the for attribute and id attribute ...where you just press tab....but keep them the same on one page dont mix it up

![[Pasted image 20241126193035.png]]


*****INPUT****

The [`input`](https://www.htmldog.com/references/html/tags/input/) tag is the daddy of the form world. It can take a multitude of guises, the most common of which are outlined below (see the [input reference page](https://www.htmldog.com/references/html/tags/input/) for the whole crazy family):

- `<input **type="text"**>` or simply `<input>` is a standard textbox. This can also have a `value` attribute, which sets the initial text in the textbox.
- `<input **type="password"**>` is similar to the textbox, but the characters typed in by the user will be hidden.
- `<input **type="checkbox"**>` is a checkbox, which can be toggled on and off by the user. This can also have a `checked` attribute (`<input type="checkbox" **checked**>` - the attribute doesn’t require a value), and makes the initial state of the check box to be switched on, as it were.
- `<input **type="radio"**>` is similar to a checkbox, but the user can only select one radio button in a group. This can also have a `checked` attribute.
- `<input **type="submit"**>` is a button that when selected will submit the form. You can control the text that appears on the submit button with the `value` attribute, for example `<input type="submit" value="Ooo. Look. Text on a button. Wow">`.


****internal styling *****
<style> goes in the <head>
of the document

to link a style sheet..type link press tab and enter the document in the "" you want it to link to in your folder
**use the link buttom if your want all the pages to match on mutli page websites


STYLING
## Using CSS

CSS can be added to HTML documents in 3 ways:

- **Inline** - by using the `style` attribute inside HTML elements
- **Internal** - by using a `<style>` element in the `<head>` section
- **External** - by using a `<link>` element to link to an external CSS file

The most common way to add CSS, is to keep the styles in external CSS files.

internal example of styling with css:
<head>
<style></style>
</head>

another example:
<!DOCTYPE html>  
<html>  
<head>  
<style>  
body {background-color: powderblue;}  
h1   {color: blue;}  
p    {color: red;}  
</style>  
</head>  
<body>  
  
<h1>This is a heading</h1>  
<p>This is a paragraph.</p>  
  
</body>  
</html>
(copy and paste a table from mdm in the style tag
*put the style element in the head of document*)



google search styling tables on mdm if you want his example during class.

***save in github.
save a repo called boilerplate styles saved in a folder there bc typing this manually is not practical. have the styling you like(you can modify it for your own needs and then save it for assignments)

*****EXTERNAL STYLING****

## External CSS

An external style sheet is used to define the style for many HTML pages.

To use an external style sheet, add a link to it in the `<head>` section of each HTML page:

### Example

<!DOCTYPE html>  
<html>  
<head>  
  <link rel="stylesheet" href="styles.css">  
</head>  
<body>  
  
<h1>This is a heading</h1>  
<p>This is a paragraph.</p>  
  
</body>  
</html>
GO ON HOME page by the <p> tag <p class (press tab)

TYPE ON CSS FOLDER THEN TYPE out larger-font or what you want it to be

on the css page go and type in this in the <body>
.larger-font {
}

another convention to use like larger font is first paragraph

***Class uses .
id uses #

(you can always move your mouse over it for help between these)

class isnt very specific...id is saying this is the one....it is very specific.
so it will always win and show more between id and class.
the computer reads from top to bottom...so the last class is going to win. 
CSS-meaning cascading styles for this very reason.
to toggle between mobile and computer websites for the zoom feature.



****RESET CSS****
GO TO GOOGLE AND TYPE RESET CSS
COPY (THE SECOND LINK) CODE BLOCK THEN PASTE IN VS CODE. (IT HELPS YOU NOT FIGHT DEFAULT MARGIN OR THE BROWSER.)
BOOTSTRAP COMES WITH THIS ALREADY SET UP. ***your reset needs to go at the top of the <head>other wise it wont work bc it will be over ridden



FONTS*****
(HIS EXAMPLE AND FAVORITE ON HIS WEBSITES)
in the body font family:arial, helvetica, sans serif}

Use of CSS color, font-family and font-size properties:

<!DOCTYPE html>  
<html>  
<head>  
<style>  
h1 {  color: blue;  
  font-family: verdana;  
  font-size: 300%;}  
p {  color: red;  
  font-family: courier;  
  font-size: 160%;}  
</style>  
</head>  
<body>  
  
<h1>This is a heading</h1>  
<p>This is a paragraph.</p>  
  
</body>  
</html>





lab 2 notes:
h1 goes in the header
 use code comments and sections of h2's h2 goes under main in main
 use src and alt, and add your tables



****LINKING WITH BOOKMARKS TO SCROLL TO A SPECIFIC PART OF THE WEBSITE****
A link does not have to link to another HTML file, it can link to any file anywhere on the web.

A link can also send a user to another part of the same page they are on. You can add an `id` attribute to just about any tag, for example `<h2 id="moss">Moss</h2>`, and then link to it by using something like this: `<a href="#moss">Go to moss</a>`. Selecting this link will scroll the page straight to the element with that ID.


## Link to External CSS

External style sheets can be referenced with a full URL or with a path relative to the current web page.

### Example

This example uses a full URL to link to a style sheet:

<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">



[styling]
best way to style an image so that it isnt overwritten by a style that might be in the head or on a stylesheet.css.

example of best styling:
<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
