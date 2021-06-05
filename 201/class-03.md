# Day 3 Reading Notes

## HTML

### Lists
- **ordered lists** lists that are typically numbered. Like a recipe or ranking. they are listed inside these tags: <.ol><./ol>
- **unordered lists** lists that are in no particular order. They are listed inside these tags: <.ul><./ul>
- **definition lists** lists that are made up of terms with their definition. They are listed inside these tags: <.dl></.dl>

Every list item inside these tags should be listed with <.li><./li>

Lists can be nested

### Boxes
CSS treats HTML elements as if it is it's own box. You can use CSS to alter the look of each box

Legiblity can be improved by controlling the width of boxes containing text

- **border** the edge of the box. Can be visible or not. You can alter the thickness, style and color.
  - style of border can be solid, dotted, dashed
- **margin** the area outside of the box. You can change the distance between boxes.
- **padding** the area between the border of the box and the content inside it. You can change the distance between the border and content.
- **background color** using 'background-color:' you can change the background color of the box
- **text align** using 'text-align:' you can move your text to the right, center, left
- **visibility** using 'visibility:hidden' you can hide your box

## JavaScript

### if/else statements
if/else statements check a condition
- if the statement is true the first code block is executed
- if the statement is false the second code block (else) is executed

### Switch statements
they start with a variable called **switch** and the entire statement lives in one code block.
- if a match is found that piece of code is run & the break statement allows you to stop the rest of the switch from running.

### Loops
Loops check if a condition is true and run its it's code block. It will repeat until the condition is false.
- **for loops** are used when you want to run the code a specific amount of times.
  - Initialization: create a variable and set it to zero. The variable to normally i & acts as a counter. example: var i = 0;
  - Condition: the loop should continue to run until the counter reached a specified number. example: i<10;
  - Update: everytimet the loop runs it adds one to the counter. Example: i++
- **while loops** are used when you don't know how many times you will need to run the code. 
- **do while** is similar to the while loop except that it will run the loop at least once even if the condition is false.

### Comparison operators
- **===** strictly true
- **!==** strictly false
- **==** true
- **!=** false
- **< , >** less than, greater than
- **<= , =>** less than or equal to , greater than or equal to




[Back to Main](README.md)