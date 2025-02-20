February 13 Notes

[https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)
-reference Mdn docs. "Grid Template Area"

www.caniuse.com
-Check if something(scrollbar) is supporter by your browser>

**highly recommend doing this every 6 months**
-dont use the help on the game instead google or use docs to help you learn
[https://flukeout.github.io/](https://flukeout.github.io/)



**HERO ELEMENT**
large nav "apple.com"
its a call to action
can have a nav above it or not
set to vh 50% might be a good place to start

#### when making a side bar nav it does NOT go in the header.

-class has higher specificity over Id. which is why he uses classes first then an Id if he needs to over ride a styling. 

**BRAND**
-***you dont need an LLC to create your own brand**

**GRID**

1.  you must wrap it for a container*
###### wrap it in a div rather than putting container on element(which you could) but using the div it isolating it. 
-leaving the body open gives you the option to use your body later for font or something later. 

css
.container:
display: grid

#contant Create your grid area now.
grid-template-areas:
*dont tab to put in values like usual*
-instead enter all the way down to have room to enter.

2. "header header"
"nav    main"
"nav    main"
"footer footer"
}
*you are basically drawing it out with words.. you can put space to see*

3. then select each one(and make it match above the grid template-area)
.header{
grid-area: header;
}

.nav{
grid-area: nav;
}

.main{
grid-area: main;
}

footer{
grid-area: footer;
}

##### optional: add background colors to see the layout

#### SETTING UP ROW AND COLUMNS
add grid-template-columns
![[Pasted image 20250213192141.png]]

then add
grid-template-rows
![[Pasted image 20250213192341.png]]
or auto or 0.5
-***you can use fr or px
![[Pasted image 20250213192524.png]]

you can also use vh
![[Pasted image 20250213193443.png]]

**how to put a scroll bar in your nav**
**USING OVER FLOW**
![[Pasted image 20250213193623.png]]
then can style it if you want webkit-scrollbar (reference mdn and caniuse.com to see about compatibility)

**OVERFLOW**
overflow-y: auto 
![[Pasted image 20250213192659.png]]
-*you can use auto or scroll*
-*use scroll if you dont have enough content*

(YOU MIGHT NEED TO ADJUST YOUR FR OR PX IN CONTAINER)

**GAP**
or also known as gutter
adding some padding might be good
![[Pasted image 20250213192618.png]]

**OVERFLOW**
overflow-y: auto
![[Pasted image 20250213192659.png]]
(YOU MIGHT NEED TO ADJUST YOUR FR OR PX IN CONTAINER)

*THE GRID TEMPLATE ROWS ARE THE HEIGHT IN THE GRID TEMPLATE AREAS
![[Pasted image 20250213192859.png]]

![[Pasted image 20250213193008.png]]

(there is a repeat function if they are all the same size) reference mdn

-fr's... arent fixed so your page will change based on the size of screen. 
-fr will scale depending on the amount of content/
-1 fr is equal 25% they are proporsonal to each other so the % chnges the more you have

#### placing a px on your nav and footer will keep it the same

mdn fr to learn more!

*you can add flexbox to grid with nesting*

![[Pasted image 20250213200905.png]]
use a selector-
a way to add multples classes on an element
![[Pasted image 20250213201734.png]]

*if the selector is confusing*
![[Pasted image 20250213201851.png]]
you can use btn

more practise with selectors
![[Pasted image 20250213201920.png]]

[https://flukeout.github.io/](https://flukeout.github.io/)

## use docs for animation
## w3schools for animation
## key schools for animation
he used transition....only one transition per selector
![[Pasted image 20250213201444.png]]
![[Pasted image 20250213201541.png]]
remove all and add background color

### play around with keyframes

