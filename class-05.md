# HTML & CSS
## 5 Images
* create an image folder within your repo 
```html
use align=(left/right) within a text element to align the image to the left or right of the text

align =(top/middle/bottom) determines where the text will start in relation to your image
```
Three Rules for Creating Images
1. Save images in right format (jpeg, gif or png)
2. Save images at the size it's supposed to be on the website 
3. Measure images in pixels rather than cm or in. 

## 11 Color
```
hsl(a): hue (0-360), saturation (%) and lightness (0-100%, 50% is normal) of the color you're using. a determines the transparency 0-1. 
```
Older browsers do not recognize HSL/HSLA so it's a good idea to add an extra color rule which specifies the color using a hex code, RGB value or color name

## 12 Text
Typeface Terminology
* serif: extra details on the ends of the main strokes of letters
* sans-serif: no extra details on main strokes
* monospace: eery letter font is the same width
* weight: light, medium, bold, black
* style: normal, italic, oblique
* stretch: condensed, regular, extended

You can use font-face to specify where a font can be downloaded from if it's not on the computer. But the user has to download the font onto their computer <br>
<br>
Best to use pixesl when determining font size in order to ensure they show up on the screen the intended size. 

```css

button:hover {} what happens when someone hovers over the button. 

input[type=radio]:active {} what happens when someone clicks the input. 

:focus what happens when an element has focus. Any element you can interact with can have focus. 
