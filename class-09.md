# CSS & HTML
# 7 Forms
Server organizes input data with name value pairs. 

```html
form controls live within a <form></form> element. 
There must be an action attribute that says the url for the page on the server that will receive the info in the form when submitted. 
```
input types:
1. text
2. password
    * can also carry size and max length attributes 
3. textarea
4. radio button
5. checkbox 
6. drop down list box
7. multiple select box 
8. file
9. submit button
10. image button - involves using an image for a submit button. 

You can use labeles on your inputs to wrap around the text description and the form input 
<br>
<br>
You can also keep the label seperate from the form control and use the for attribute to indicate which form control it is a label for. 
<br>
<br>
You can use form validation to make sure that a form is filled out properly. requipred = 'required'

## 14 Lists, Tables, and Forms
list-style-position: (outside/inside) --> sits to the left or within the line of text. <br>
<br>
You can style more than just boxes: 
* inputs
* submit buttons
* fieldsets/legends    
* cursor 

# JavaScript & JQuery
##  6 Events

Events are fired or raised. <br>
<br>
events trigger a function or script.
<br>
<br>
How events trigger javascript code
1. select element node(s) you want the script to respond to 
2. indicate which event on the selected nodes will trigger the response. 
3. state the code you want to run when the event occurs (can be named or anonymous);

3 ways to bind an event to an elemnt
1. html event handlers (DO NOT USE);
2. traditional dom handlers
* can only attach one function to any event 
3. dom level 2 event listners 
* allow one event to trigger multiple events 

```js
event listners
element.addEventListner('event', functionName, [boolean])
```

You can use functions w/ paramaters w/i their event listeners. 

```js
const el = document.getElementById('id')
el.addEventListener('event', function() {
    namedFunction(parameter);
}, false)
