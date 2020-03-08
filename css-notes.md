# css notes


## Navigation
1. [Home](README.md)

[CheetSheet](css-cheetsheet.md)

anything with *this* style is notes that have beed copied from sources and will be rewriten as i have time!

### What is CSS?

- C.S.S stands for Cascading Style sheets
- creates the details for the site your creating ie the colors and the shapes. it does this by modifying how things are displayed
- it can be utilized either in the html file its self for small projects or usualy in its own file
    - you can put css in the html file via `<style>` or its own via `<link>` but external files are preferd for most css
- a css rule or declaration looks like this: `selector {property: value,vlaue;}` see the cheetsheet for details on this


### adaptive sizing notes

- *Content on a website can be sized relative to other elements on the page using relative measurements.*
    - *The unit of em sizes font relative to the font size of a parent element.*
    - *The unit of rem sizes font relative to the font size of a root element. That root element is the <html> element.*
- Percentages are commonly used to size box-model features, like the width, height, padding, or margin of an element
    - *When percentages are used to size width and height, child elements will be sized relative to the dimensions of their parent (remember that parent dimensions must first be set).*
    - *Percentages can be used to set padding and margin. Horizontal and vertical padding and margin are set relative to the width of a parent element.*
-  when one width or height is defined the other can be set to `auto` to make it scale properly.


### Some usefule things to remember with css

- rules are structured with a selector folowed by a declaration `<tag {thing your making the tag do!;other thing you want it to do;}>`
- linking in looks like `<link href="css file link" type="text/css" rel="stylesheet" />`
- inline elements flow within the text w/o starting a new line
- block elements start a new line with each element
- css changes how things are displayed
- style use goes in head



### Usefull code snips (this may move to annother page)

example of scaling for images
>.container { 
	width: 50%; 
	height: 200px
	overflow: hidden
.container img { 
	max-width: 100%; 
	height: auto; 
	display: block;
