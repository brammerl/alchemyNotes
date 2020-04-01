# HTML & CSS
## 3 Lists
Html provides us with 3 types of lists:
1. **Ordred Lists**: lists where each item in the list is numbered
2. **Unordered Lists**: lists that begin with a bullet point
3. **Definition lists**: made up of a set of terms along with the definitions of those terms 

```HTML
Definition Lists: 

<dl></dl> usually consists of a series of terms and their definitions
inside  the dl element you will usually see pairs of <dt> and <dd> elements 
<dt> : used to contain the term being defined
<dd> : used to contain the definition

<dl>
    <dt>Word</dt>
    <dd>Definition</dd>
</dl>
```

```HTML
Nested Lists
<ul>
    <li>List Category</li>
        <li>List Object</li>
    <li>New list category</li>
<ul>
```

```css
:10
.container
    margin: 100px auto;
    height: 500px;
    width: 50%;
    border: 2px solid black;
    padding: 20px;
    background: -webkit-linear-gradient(rgb(245, 183, 90), rgb(231, 175, 123));
    border-radius: 50px 50px 50px 50px;
    box-shadow: 2px 2px 5px 2px;
}

wrap your content in <div class='container'> then use this
``` 
## 13 Boxes
1. Control the dimensions of your boxes <br>
* Box Dimensions: **width** and **height** --> designers have started to use % and ems to create flexible designs across different devices <br>
* **min-width** and **max-width**: ensure that contents are legible especially on smaller screens. <br>
* **min-height** and **max-height** <br>
* **overflow**:  tells the browser what to do if the content contained within a box is larger than the box itself. Can have 1 of 2 values: <br>
    1. **hidden:** hides any extra content that does not fit. 
    2. **scroll**: adds a scrollbar to the box so that users can scroll to see missing content. 
2. Create borders around boxes
* Border values:
    1. thin
    2. medium
    3. thick
* Border styles
    1. solid
    2. dotted
    3. dashed
    4. doubled
    5. groove
    6. ridge
    7. inset
    8. outset
    9. hidden/none
* can individually change style of diff borders
    1. border-(top/left/right/bottom)-style
* border-color: border-(top/right/bottom/left)-color: 
    * shorthand: border-color: color1 color2 color3 color4; 
* shorthand: border: 3px dotted color; 
3. Set margins and padding for boxes
**padding**: allows you to specify how much space should appear between conent of element and its border <br>
**margin**: controls the gap between boxes. <br>
<br>
centering content<br>
* make sure you have a set width
* set the left and right margin to autos
4. Show and hide boxes 
* **display**: allows you to turn an inline element into a block-level element or vice vesa  <br>
1. **inline**: acts like an inline element
2. **block**: act like a block-like element
3. **inline-block**: causes a block level element to flow like an inline element while retaining features of a block-level element 
4. **none**: hides an element from the page and the element acts as though its not on the page at all. 

# JavaScript & JQuery
## Switch Statements
```js
switch(level) {
    case 'one': 
    code block 
    break;
    
    case 'two': 
    code block
    break;
    
    case 'three':
    code block
    break; 

    default: 
    code block
    break;
}
```
If...else | Switch 
|---|---|
| * Thre is no need to provide an else option| * You have a default option that is run if none of the cases match|
|* with a series of if statements, they are all checked even if a match has been found| * if a match is found, then the break statement stops the rest of the switch statement from running (providing better performance than multiple if statements)| 


