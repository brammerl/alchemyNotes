The goal: 
* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn't transmitted to the server. 

Different companies were releasing solutions unique to their browsers/programs. How do we create a standardized API, implemented natively and consistently on 3rd party plug ins? <br>

HTML5 is supported across all internet browsers. It's a way for web pages to store named key/value pairs locally w/i the client web browser. The data persists even after you navigate away from the website/close the browser. <br>
<br>

Storing data other than strings need to use functions like parseInt() and parseFloat(). <br>
<br>

You can use .getItem() to get already existing data and .setItem() to create new data. <br>

## Limitations
* 5 mgs for storage space each origin gets by default. 
* everything is stored as a string so it's important to initialize your non-string values back. It's easy to get lost/mixed up. 