# HTML Text

While creating a webpage, there are some basic things one will need to know such as how to create content for the actual page. 

There are headers tags which go from h1 which is the largest header down to h6 which will be the smallest header. ``` <h1></h1> ``` through ``` <h6></h6> ```.

To write a paragraph, put the text between p tags such as ``` <p>text goes here </p> ```.

For bold or italicized put the content between ``` <b></b> ``` for bold and ``` <i></i> ``` for italic.

For superscript and subscript, use the following; ```<sup></sup> ``` for superscript and ``` <sub></sub> ``` for subscript.

If you do not want a sentence to go all the way across the page use the ``` <br /> ```.

To put a horizontal line through the page then use the ``` <hr /> ```.

For quotations there are two different ways to do so. Blockquote ``` <blockquote></blockquote> ```. For a quote that will go inside a sentence use ``` <q></q> ```.

# CSS

CSS is what gives the webpage color and style. Each of the html tags that are being used can be used in the CSS. When writing code for CSS a programmer needs to pick the selector which will be a tag from the html such as p, for paragraph and declare something for it. For example  ~~~ p {
	font -family : Ariel
}~~~

Each selector needs property like font-family and a value like Ariel as seen on the above code. One can use CSS inside the actual html file or one can create a CSS file and link it to the html file. ``` <link href=”css_style.css”> ```. This code will go between the head tags on the html page, which will allow the browser to know where to look for the CSS code.

For a universal selector use *, for a class selector use (.) and for an id selector use #.

# Basic JS instructions

JS statements are instructions to the computer on how it should run. Each of the statements on JS should end with a semicolon (;). Also, while writing code a programmer can write notes to themselves or their team as to what and why they are writing a specific code. There are two different ways to write a comment which are ``` /* for multiline code */ ``` and ``` // for single line code ```.

Variables are code that holds a value. How does one work with variables? First one needs to declare a variable by using the variable key word such as let, var, or const. Then they need to assign the variable a name and value. For example ``` let name = ‘Jon’ ```.

Variables can hold many different data types. 

- Numerical which are numbers
- String which consists of letters and other characters. Each string data needs to be in a single quotation such as ‘’ or double “”.
-Boolean which are true and false.
- Arrays hold many data values such as a list.


When using variables one of the key elements is naming a variable with a good name and there are a few rules one needs to follow while naming variables.

1. Variable names must start with a letter, underscore or with a dollar sign.
2. The name can use letters, underscore or dollar sign.
3. One can’t use a keyword. Key words can be found by googling them and using other coding resources.
4. Variables are case sensitive and if you are using two or more words, the first letter in the name is not capitalized but the second word first letter is such as firstName.
5. When naming a variable use something specific as to what the variable data is holding.

An expression is a variable and the value. A variable can hold one value or more. When writing an expression they need operators to help the computer identify the type of expression being written. There are many different types of operators to help the computers.

- Assignment operator =
- Arithmetic operator +, - , *, /
- String operator ‘’ or “”
- Comparison operator <, >, <=, >=
- logical operator &&, ||, !

# Decisions and Loops

Written code for the computer can somewhat be like a flowchart. With a flowchart there will be different paths to go down and even start over. Just like flowcharts for a business, a computer can read code like a flow chart using decisions and loops.  For the computer to do this there needs to be comparison operators used in the code.

- == equal to
- === strict equal to
- != not equal to
- !== strict not equal to
- and <, >, <=, >=
- && Logical and. Both conditions must be true for the return to be true.
- || logical or, only one condition needs to be returned for a true.
- ! logical not, this takes a condition and inverts it.


If statements can be used as well. If statements will check a condition and if that condition is met then the code will execute.

If else statements will look at the code expression and check to see if the condition is met and if it is then the first expression will execute but if it does not meet the condition in the first expression then the second (else) expression will execute.

- [Back to Main](README.md)
- [To 201 Table of Contents](class_201_notes.md)
- [To 102 Class Notes](class_102_notes.md)