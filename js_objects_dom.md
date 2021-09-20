# Objects in JavaScript

In Javascript one will be able to group together variables that are called property. Functions within an object are called methods. Objects will have name/value pairs. The key value pairs will be the variable name and the value will be a string, number, boolean or an array.

```
Var home = {
	name: “barn”,
	rooms: 5,
	swimmingPool: true,
	roomType: [“master’, “kids”, “office”];
```

Then have a function to call it. You will have a key and the value and the value will be function.

# Document Object Model (DOM)

DOM will help browsers identify the model of the html page and how JS can access it. In essence the browser will turn the html into a tree and by using keywords in JS, it will allow the programmer to grab things from the html page and use it in JS.

The programmer will need to access elements by using keywords such as getElementById(), or getElementByClassName() and then work those elements that are being called. When getting queries it may return just one element or it may return a node list.

Elements can be called by using a class attribute such as getElementByClassName(‘class name’). Elements can be called using a tag name such as getElementByTagName(‘tag name’). They can be called by using CSS selectors. Once will be able to loop through nodelist by using a for loop.

Traversing the DOM can be done by using either

- parentNode
- previousSibling
- nextSibling
- firstChild
- lastChild 

While traversing the DOM be mindful that some browser will add white space to the tree.

John Wiley & Sons Inc. (2013). JavaScript & JQuery. 

- [Back to Main](README.md)
- [To 201 Table of Contents](class_201_notes.md)
- [To 102 Class Notes](class_102_notes.md)