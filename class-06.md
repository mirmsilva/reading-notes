# Day 6 Reading Notes

## Javascript

### Objects

objects group together a set of variables an functions to create a model of something in the real world

Stuff to know about objects:
- variables become known as **properties**
- functions become known as **methods**
- the value of a method is always a function
-  properties and methods are called **keys**
- functions can be string, number, boolean, array or other
- an object cannot have two keys with the same name

### Document Object Model

specifies how browsers should create a model of an HTML page & how Javascript can access & update contents of a webpage while its in the browser

the DOM is neither HTML nor Javascript. It is a seperate set of rules. 

it consists of 4 major nodes:
- **document node** 
- **element node**
- **attribute node**
- **text node**

You can select nodes by their id or class attributes, tag name, or css selector syntax

from an element node you can access and update its content using properties like textContent or DOM manipulation techniques

### Const
a way to declare variables that can never be changed

'const newVariable = 'unchanging';'

constant literals:
a new way to write strings
wrap drting in backticks & wrap variables in ${}

"`Here is my string, and my variable ${variable}`"

[Back to Main](README.md)