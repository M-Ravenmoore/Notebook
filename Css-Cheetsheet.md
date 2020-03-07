## cheet sheet

## Navigation
1. [Home](README.md)
1. [Css Notes](css-notes.md)


### - linking in looks like `<link href="css file link" type="text/css" rel="stylesheet" />`


**Element tags** | **What it looks for**
--------------|-------------

`* {}` | universal selector apply changes to all elements in the document
`tag {}` | type selector targets elements with this tag type
`.'class' {}` | matches to `class=''` attribute defined behind the dot
`#'tag-id here' {}` | matches to `id=''` attribute defined behind the hash ids hold highest priority for an element
`tag>tag2 {}` | child selector selects a child of a tag to be modified
`tag tag {}` | descendant selector targets an element within an eliment
`tag+tag {}` | adjacent sibling selector targes elements that follow a nother type of element but no others


**Attribute tags** | What they do ish
-------------------|------------------
`!important` | at the end of a css rule makes it override any other conflicting rules, **NOT COMMON USE ANYMORE!!!!**
`font-size {}` | changes the size of the font with in associated element useing a variaty of measurments including pixels(px) or point(pt)
`color: ` | changes the color of the main object in an element
