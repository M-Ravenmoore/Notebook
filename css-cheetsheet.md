## cheet sheet

## Navigation
1. [Home](README.md)
1. [Css Notes](css-notes.md)


### - linking a css file into html looks like `<link href="css file link" type="text/css" rel="stylesheet" />`

## Selectors
selectors indicate which element you want to modify, rules can apply to multipal selectors at once when you seperate them with commas.
below is a list of some examples

**Selector** | **What it looks for**
--------------|-------------
`* {}` | universal selector apply changes to all elements in the document
`element`| this is a 'type selector' and it targets elements that would have a `<element>`
`.class'` | matches to `class=''` attribute defined behind the dot
`#id'` | matches to `id=''` attribute defined behind the hash ids hold highest priority for an element
`element > element2 ` | child selector selects a child of a element to be modified
`element element` | descendant selector targets an element within an eliment
`element + element {}` | adjacent sibling selector targes elements that follow a nother type of element but no others



**Property** | What they do ish
-------------------|------------------
`!important` | at the end of a css rule makes it override any other conflicting rules, **NOT COMMON USE ANYMORE!!!!**
`font-size: measurement ;` | changes the size of the font with in associated element useing a variaty of measurments including pixels(px) or point(pt)
`color: color;` | changes the color of the main object in an element
`background-color: color;` | changes the background color of an element
`float: left;` | removes the object from normal flow and assigns it a justification ie left in this case
`min-width: measurement;` | sets minimum width of an element
`max-width: measurement;` | sets the max width of an element
`min-height: measurement;` | sets the min height of an element
`max-height: measurement;` | sets the Max height of an element
`background-size: ` | allows you to set your background image size with in an element.


**values** | What they do
-----------|-----------------
`inherit` | gives the property the inherited value of the elements parent.
`rgb` / `rgba` | color code in Red Green Blue (rgba is for opacity)
