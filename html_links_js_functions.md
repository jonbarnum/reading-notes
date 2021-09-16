# HTML Links

On the webpage there can be found links to take you to other pages and or different areas on the webpage. As a programmer you can do that too by creating an element that looks something like this, ``` <a href=”internet website goes here”>Text goes here</a>```. These links can be from different websites or it can be used from different files from a local computer for example ``` <a href=”about.html”></a> ```. The example is from a file that is in the same folder as the main html page. If the link comes from a file that is within a folder of the main folder it would look something like this ``` <a href=”documents/final.html></a> ```. A programmer can add email links such as ``` <a href=”mailto:me@example.com”>email me</a>```. If you would like to have the link open into a new tab then add target=”blank” after the website. Links can also be set up to send the user to different parts of the page. This can be done by ``` <a href=”#anidselector”>Id selector name</a> ```. Someone where on the page one needs to set an id selector for a different part of the page so that can be used.

# CSS Layout

When creating the CSS portion of the webpage, one needs to remember that everything is a box. There are block-level elements which extend all the way across the page. There are inline line elements that allow text to wrap around other blocks with the section of blocks. A programmer can have many boxes with a section. 

For position static there is no need to type that in because the computer is set for that. When you want to switch it from the norm then put in something like this:

```
body {
	position:  relative;
	top: 15px;
	left: 110px;
}
```

There are different positions one can place their boxes. Here is a list of different options for the programmer.

- position: relative
- position: absolute
- position: fixed
- z index (allows for overlapping of different elements)
- float: allows text to be wrapped around other boxes

If you want to add columns to the page then use a div tag and name it. Then in CSS call the id and add float position to it.

Another thing to remember is that there are different screens that are different sizes. So when coding, think about the audience that will be looking at the page and what they will most likely be using. A programmer can use the dimensions of the screen size to help create awesome web pages.

# JavaScript Functions and Methods

Functions are a group of statements that are grouped together so the browser knows what to execute. Browsers need very clear detailed instructions on what it is supposed to do. This is why functions are very important because it will let the browser know what to do. 

How to declare a function. First start off by typing the function then give the function a name if you are going to call on it later, then () {}. If the function needs parameters then they will go inside of the () and the code will go into {}. Example:

```
function sayHi () {
	console.log(‘Hello World’);
}

sayHi(); // will console Hello World
```
The sayHi () is calling the function. 

Putting parameters in the () allows the code to know where to look to help execute the right thing. For example

```
function calculateArea (width, height) {
	return width * height;
{
 
calculateArea (3, 2);
```
This will pass 3 and 2 within the return which was width times the height to give a value. Another way to do the same function is declare the variable first, for example;

fenceWidth = 3;

fenceHeight = 2;

calculateArea ( fenceWidth, fenceHeight); 

As you are creating a function, remember the scope of the variables. There is local scope that goes within the {} and can only be used for that function. It can’t be called on later. If you have variables outside of the {} then that means they are global and can be used on other codes, however be careful with global variables because the naming of them can conflict later on with other code.


Duckett, J. (2011). Html & Css: Design and build web sites. Wiley. 
Duckett, J. (2014). JavaScript & jQuery ; Html & Css. John Wiley & Sons. 


- [Back to Main](README.md)
- [To 201 Table of Contents](class_201_notes.md)
- [To 102 Class Notes](class_102_notes.md)