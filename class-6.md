# JS & CSS 

```js
var hotel= {
    name: 'quay',
    room: 40,
    booked: 24,
    room: ['twin', 'double', 'suite'],
    checkAvailability: function() {
        return this.rooms-this.booked;
    }
}
```
you can utilize key-value pairs within a function. <br>
Nodelists:
* getElementsByTagName();
* getElementsByClassName();
* querySelectorAll('li[id]'); <br>
 gets all list with an id element. <br>
 can also get elements using css selectors <br>

 Looping Through a Nodelist
 ```js 
 var hotItems = document.querySelectorAll('li.hot');

 if (hotItems.legnth > 0) {
     for (var i = 0; i < hotItems.length; i++) {
         hotItems[i].class = 'cool';
     }
 }
 ```

Some browsers can add text node to whenever they come across white space between elements. Avoid using certain DOM properties to make sure this doesn't happen. <br>

It is safe to use them when there are no white spaces between the elements. Such as lists. <br>
<br>
Be careful what you use in your HTML and JavaScript so that way people can't acess your info and change it/introduce malicious content.  <br>
<br>
```
use document.getElementbyId().hasAttribute() to make sure an element has a certain attribute and to create certain actions if a element does in fact have that attribute. 

.className: assigns a class name to the element in question
.setAttribute('class', 'cool'): sets the class element to cool. 

.removeAttribute('class'): removes the class attribute for that element w/ a specific id. 
```


