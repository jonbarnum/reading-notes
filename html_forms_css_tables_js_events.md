# HTML Forms

Forms are an integral part of a webpage. There are many different uses for a form. Form uses include: search engine bar, text input, password input, radio buttons, checkboxes, drop-down menu options, submit buttons, image buttons, and uploading files. To start off a programmer will need to start with ``` <form></form> ``` . There will need to be an input for example text, ``` <input text=”input”/> ``` . Password works the same way, ``` <input type=”password”/> ``` . For a text area ``` <textarea name=”comments”/> ``` . For a radio button ``` <input type=”radio”/> ```. Checkbox ``` <input type=”checkbox”/> ```. For a dropdown menu start off with the form then inside of the form element add ``` <select></select> ``` then within the select add ``` <option></option> ```. File input will look like ``` <input = type”file”/> ```, submit button ``` <input type=”submit”/> ``` .For an image button ``` <input type=”image”/> ```.

 # CSS list, tables and forms

For an unordered list you can change the marker for the list to none, disc, circle, or square. For an ordered list you can change it to decimal, decimal leading zero, lower alpha, upper alpha, lower roman and upper roman. Call ul or ol depending what type of list you are using then add list-style-type: and that you would like. To have the marker move, one call list-style-position: inside or outside. Inside will place the markers inline with the other text. 

For table properties one can adjust the width, padding, text-transform, letter-spacing, font-size, border-top, border-bottom, text-align, background-color, and hover. Border spacing will add a gap between the cells and the border-collapse will take out any space between the cells. 

A web programmer can style text inputs as well such as: font-size, color, background color, border, border-radius, rocus, hover and background-image. 

Styling submit buttons- color, text-shadow, border-button, background-color, hover. 

Cursor styles- auto, crosshair, default, pointer, move, text, wait, help and you can grab one from the internet.

 # Javascript Events

An interaction between the user and the webpage creates an event that triggers code and code then responds to the interaction. There are many different types of events. For UI events there are load, unloadm error, resize and scroll. For mouse events: click, dblclick, mousedown, mouseup, mousemove, mouseover, and moutout. Form events include: input, change, submit, reset, cut, copy, paste, and select.

There are three ways to get an event on an element. The first way is an html event handler attribute but current standards state this is bad practice so do not use it. The second is a DOM event handler and third an event listener. The DOM event handler the programmer needs to identify the element then the event and assign it to code, element.event = code. Event listeners will look something like this element.addEventListener(‘event’, ‘code’, [boolean]);. Depending on how old the web browser is will depend on if the programmer needs to add additional code to support it.

User interface events which listed earlier are load, eunload, error, resize, scroll.

Duckett, J. (2011). Html & Css: Design and build web sites. Wiley.
John Wiley & Sons Inc. (2013). JavaScript & JQuery. 


- [Back to Main](README.md)
- [To 201 Table of Contents](class_201_notes.md)
- [To 102 Class Notes](class_102_notes.md)