# Defining Styles

## Objectives
* identifying when to use a class vs id
* create styles for id to help position elements using position, left, right, top, bottom, width and height
* to use z-index to specify layer

We have looked at style classes to help create reusable styles that can be placed anywhere in the document:
```
<style>
  .eg { color: red;}
</style>

<span class="eg">This text is red</span>
```

There is another selector, the **id**.  selector ID's differ from classes in that the class is intended to be used many times, but an ID is to specify a unique element.  

Consider this example.  A book may have many chapter titles, so we might specify those as classes.  However, there is only one book title, and that might be specified as an ID.


### Style Selector ID
* An ID is defined with a hashtag (#) followed by the name of the id
* An ID can be assigned to a specific element, but ID's should be unique

### What is the difference between an ID and a Class?

An ID is intended for unique elements on the page. Think about a button that does a task, like a Save Button.  You only have 1 Save button on a page.
A Class is a reusable style.  Maybe you have a roster for a team, and all of the Tanks need to have one style, and all the Smashers need to have another style.

### Positioning

You can put multiple sections on a page, kind of like using text boxes in Microsoft Word.  We use the position style.  Today we will look at the most basic position: absolute

This creates floating elements in the page, where you set the position in pixels from the top/left of the page, and you set the width and the height.
Look at page2.html for an example.

A page can be imagined as being a coordinate plane, except the (0,0) coordinate is at the top left of the page, but the first number shows the horizontal (x) coordinate and the second shows the vertical (y) coordinate. We can use these coordinates to move blocks of html around the document by using the *position* style along with the *top* and *left* styles.  We can use these styles to create a "text box" or a page within the page.  This block or box can have its own html that is separate from the rest of the page.

How do you put one element/block in front of another if they overlap? Z-index is the style that determines order on a page.  Higher numbers are placed on top of lower numbers!

### Floating elements
There is a style called ***float*** that works to take block elements and wrap inline elements around them.  Take a look at float.html for some examples.


## Assignment

Open up the document called assignment.html.
There are several short stories in here.  Move each one into its own block, and display them on your page in an attractive format.  You should find a picture that you can include with each one.  You may want to consider the use of the float style for images.  See the example file, float.html
