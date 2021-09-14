# HTML Lists

There are a few different types of list that can be used while creating html. They are ordered lists, unordered lists.

``` <ol></ol> ``` for ordered list which will number each item in the list.
``` <ul></ul> ``` for an unordered list which will give a bullet point for each item in the list.

Each of the lists will have ``` <li></li> ``` which is a list item that you wanted listed.

There are two other types of lists that can be used as well, which are definition list and nested list.

For definition list use ``` <dl></dl> ```. Use ``` <dt></dt> ``` to use for the term and ``` <dd></dd> ``` for the actual definition.
For the nested list use 
```
<ul>
	<li>
		<ul>
		<li>
		</li>
		</ul>
</li>
</ul>
```
This will nest the list items.

# CSS Boxes

While implementing CSS for a webpage a programmer needs to think of everything on the page as a box. When thinking about the webpage as a whole bunch of boxes then it becomes easier to understand how to format the page and what it will look like for the finished product. 

For box dimensions there are two dimensions to think about, width and height. Both of these can be controlled through using px or % when controlling through CSS.

~~~
p {
	height: 200px;
	width: 150px;
}
~~~
Or
~~~
p {
	height: 50%;
	width: 45%;
}
~~~

If a programmer wants to fit the page to different sizes of screens, there is an option to limit width and height. For limiting width a programmer needs to put in a min-width and a max width.
The same goes for height, min-height and max-height. If there is too much content for the box a programmer can control what happens to the information that is trying to extend past the box. The programmer will need to call the element then use word overflow:hidden or overflow:scroll. Hidden will hide the information and scroll will allow a scroll bar to exist to see it.

Each box itself has a couple of elements to it. There will be a border, margin and padding each of those can be called upon and changed to fit the specific needs of the programmer.

## Border

The border-width can be changed by using px or using the words thin, medium, and thick. The programmer can change each side of the border as well by using border-top-width:. Border-right-width:, border-bottom-width:, and border-left-width.  The style of the border can be changed as well by using border-style: and solid, dotted, dashed, groove, ridge and hidden to name a few. A border can have color as well by using border-color: add any color as one will like. Each side of the border can be called as well just like the example with the border height. 

## Padding and Margin

Padding and Margin each can be called and changed by using a % or px just like the border thickness. Each side of the padding and margin can be called as well just like the example of the border width.

## Centering Content

Boxes can be centered in a couple of different ways. First is doing a text-align: center and the content within the entire box will be centered. Remember boxes will go across the entire screen. If one would want the box itself to be smaller and centered in the middle of the screen then the programmer will need to adjust the box dimensions such as width and padding. 

## Change inline/block

To get multiple boxes on the same line then one needs to do a display:inline. However this needs to be done within a group of grouped items.

# JavaScript

## Switch Statements

A switch statement gives different values that the code could use. Depending on what value is matched depends on what code will be executed. In essence there will be code that needs to be executed and it will look through a list of different values and once it has a value that matches what the code needs then it will execute.

## Truthy and Falsy Values

Falsy values include variables assigned false, a variable with a value of 0, variable with a value with empty string “ “, NaN (not a number), and a variable with no value assigned to it. When doing comparison it is important to note that the === and the !== will be stricter and give less values than == and !=.  The logical operation moves from left to right as well.

## Loops

Loops will take a code block and check a condition. If the loop finds something that is true then it will execute the code. If not then it will continue to work through the loop looking for something that is true. An example;
``` for (let i = 0; i < 5; i++) ``` when you document for i, it will start at 0 and ask if 0 is less the 5 and then it will increment by 1 then start at 1 and ask if it is less than 5 and go through this process until it gets to 5 which then make the loop stop because 5 is not less than 5. The let i = 0 is what is called the initialization, i < 5 is the condition and the i++ is the update. A quick note; if the loop never returns a false then the loop will go on forever. There are different types of loops as well. In the above example code is a for loop which will run through an array of items. A while loop is very similar, however the variable needs to be declared outside of the loop.The Do...while loop is very similar as well. The variable needs to be declared outside of the loop and it must be executed once.

Duckett, J. (2014). Basic JavaScript Instructions and Decisions and Loops. In JavaScript & jQuery ; HTML & CSS. essay, John Wiley & Sons. 
Duckett, J. (2011). List, Boxes. In HTML & CSS: Design and build web sites. essay, Wiley. 

- [Back to Main](README.md)
- [To 201 Table of Contents](class_201_notes.md)
- [To 102 Class Notes](class_102_notes.md)