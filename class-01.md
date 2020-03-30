# HTML & CSS
## Structure 


```html
<html>
	<body>
		<h1>This is the Main Heading</h1>
		<p>This text might be an introduction to the rest of the page. And if the page is a 
			 long one it might be split up into several sub-headings.<p>
		<h2>This is a Sub-Heading</h2>
		<p>Many long articles have sub-headings so to help you follow the structure of what 
			 is being written. There may even be sub-sub-headings (or lower-level headings).
			 </p>
		<h2>Another Sub-Heading</h2>
		<p>Here you can see another sub-heading.</p>
	</body>
</html>
```

**elements**: usually made up of 2 <br>
* **tags**: opening and closing **tags**. <br>
Act like containers. They tell you something about the information that lies between their opening and closing tags.

## Attributes tell us more about elements
* made up of two parts: **name** and **value** 
* attributes are often pre-defined or follow a stipulated format. 

```html 
<html>
	<head>
		<title>This is the Title of the Page</title>
	</head>
	<body>
		<h1>This is the Body of the Page</h1>
		<p>Anything within the body of a web page is displayed in the main browser window.</p>
	</body>
</html>
``` 

content management systems: blogging platform, or e-commerce application. 
* usually allow you to edit parts of the page rather than the entire page. 

## 8 Extra Markup
* **id attribute**: uniquely identify an element from other elements on the page
* **class attribute**: a way to identify several elements. 

### Grouping Text and Elements Inline
**block elements**: elements that always appear to start on a new line in the browser window. <br>
**inline elements**: will always appear to continue on the same line as their neighbouring elements. 

```html
<div></div>
```
* allows you to group a set of elements together in one block-level box. 
* you can use id or class attribute 

```html
<span></span>
```
* acts like an inline equivalent of the div element. 
1. contain a section of text where there is no other suitable element to differentiate it from its surrounding text. 
2. Contain a number of inline elements 
* can use class or id attribute 

```html 
<iframe>
    width =
    height = 
    src = 
</iframe>
```
* a little window that has been cut into your page - and in that window you can see another page (ie a map)

## HTML5 Layout
```html
<nav></nav>
```
used to contain the major naviagional blocks on the site such as the primary site navigation 

```html
<article></article>
```
acts as a container for any section of a page that could stand alone and potentially be syndicated. 

```html
<aside></aside>
```
has 2 purposes depending on whether it is inside an article or not. 
* inside: it should contain information that is related to the article but not essential to it's everall meaning (ie. pullquote or glossary might be considered an aside to the article it relates to.)
* outside: acts as a container for content that is related to the entire page (ie. llinks to other sections of the site, a list of recent posts, a search box etc. )

```html
<section></section>
```
* groups related content together and typically each section would have its own heading. 
* it may contain several distinct article elements 
* can also be used to split up an article into sections 

```html
<hgroup></hgroup>
```
to group together a set of one or more ```<h1<>``` through ```<h6>``` elements so they are treated as one single heading. 


```html
<input>
```
Many forms need to gather information such as dates, emails, addresses and URL's 
* can give the tpye attribute several things: 
1. email
2. url
3. search

on any text input: text will be shown in the text box until the user clicks in that area. 

```html
<figure>
    <figcaption></figcaption>
</figure> 
```
Used to contain any content tht is referenced from the main flow of an article. 
* Should only bed used when the content simply referneces the element (and not for something that is absolutely integral to the flow of a page)

```html
<a><a>
```
* can place this around a block level element that contains child elements. This allows you to turn an entire block into a link. 

### Helping older browsers understand 
* older browsers that do not know the new html5 elements will automatically treat them as inline elements. 
* to help older browsers, you should include the line of css that makes the elements a block display. 

```html
header, section, footer, aside, nav, article, figure, caption {
    display: block; 
}
```
## 18 Process & Design
Questions to ask yourself
* who is the site for 
* why people visit your site
* what are your visitors trying to achieve 
* what information your visitors need
* how often people will visit your site

Use a site map to organize the layout of your entire site and how people will navigate it. 

# JavaScript and JQuery 
## 1a What is a Script and How do I Create One? 

A script is a series of instructions that a computer can follow to achieve a goal. <br>
<br>
Start with the big picture of what you want to achieve and break down into smaller steps. 
1. define the goal
2. design the script 
* split the goal out into a series of tasks that are going to be involved in solving the puzzle. (flowchart)
* write down the individual steps that the computer needs to perform in order to complete ach individual task. 
3. code each step 

Web browsers are programs built using objects 
* **document** object reprsents the entire webpage. all web browsers implement this object 