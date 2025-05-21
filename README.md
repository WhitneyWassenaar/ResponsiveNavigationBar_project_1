# ResponsiveNavigationBar_project_1
Exercise of creating a responsive navigation bar

## List of projects I made
1. <a href="https://codepen.io/Wassenaar/pen/QwwXdVj">First project</a>
2. <a href="https://codepen.io/Wassenaar/pen/JoogGVz">Edelsteen vrouwtje (Gemstone lady)</a>

## Monday | 19-5-2025 | 10:25
Today is a great day because it's my birthday! I'm now 26 years old!<br>
For this exercise I'll try to create a responsive navigation bar. <br>I follow the tutorial video: <a href="https://www.youtube.com/watch?v=U8smiWQ8Seg&t=683s">How to create a Responsive Navigation Bar (for beginners)</a> from Coding2Go.

## Tuesday | 20-5-2025 | 13:53
When building the responsive navigation bar, a few questions arose and went on a research for anwsers:

1. What is the difference between list-style and list-style-type?
   ><b>List-style</b> specifies all the list properties in one declaration.<br>Example: list-style: type position image.
   ><br><br><b>List-style-type</b> sets some different list styles. Example: square, circle, upper-roman, lower-alpha<br>
   ><img src="https://global.discourse-cdn.com/freecodecamp/original/4X/8/5/e/85ec24409f3b06da649004c0cb3297a201de1308.png" width=250>
    ><br><b>List-style-position</b> specifies the position of the list-item markers. Example: outside, inside <br>
    ><img src="https://global.discourse-cdn.com/freecodecamp/original/4X/5/7/d/57dacfef3f25827b6810e0b03092d76182512573.png" width=250><br>
    ><b>List-type-image</b> specifies an image as the list-item marker in a list.<br>
    ><img src="https://global.discourse-cdn.com/freecodecamp/original/4X/d/4/0/d40ba25e4b686a11c0cf65f40e104786b0e5a42f.png" width=250>
    
3. Which properties should you assign to * selector? For example the font-family, why in the body and not in * ? Because * means all?
   >I found the answer in the <a href="https://stackoverflow.com/questions/42925682/where-to-set-font-family-body-or-html-element">topic of StackOverflow</a>. The body element represents the content of the document. Since font-family is a property of styled content, it would seem logical to apply it to the body.<br><br>The universal selector selects and can style all HTML elements on the page. You can assign properties like font-color, background-color etc.
   
5. How many values can you use for backdrop-filter?
   >There different types of backdrop-filter values. You can also use multiple at once.<br><br>
   ><code><b>Keyword value </b>
   backdrop-filter: none;
   ><br>
   <b> URL to SVG filter </b>
   backdrop-filter: url(common-filters.svg#filter);
   ><br>
   <b>filter-function> values</b>
   backdrop-filter: blur(2px);
   backdrop-filter: brightness(60%);
   backdrop-filter: contrast(40%);
   backdrop-filter: drop-shadow(4px 4px 10px blue);
   backdrop-filter: grayscale(30%);
   backdrop-filter: hue-rotate(120deg);
   backdrop-filter: invert(70%);
   backdrop-filter: opacity(20%);
   backdrop-filter: sepia(90%);
   backdrop-filter: saturate(80%);
   ><br>
   <b>Multiple filters </b>
   backdrop-filter: url(filters.svg#filter) blur(4px) saturate(150%);
   ><br>
   <b> Global values </b>
   backdrop-filter: inherit;
   backdrop-filter: initial;
   backdrop-filter: revert;
   backdrop-filter: revert-layer;
   backdrop-filter: unset;</code>
   <br>
7. What does top, right left mean?
   >The top, bottom, left, and right properties are used with position to set the placement of an element. They only have an effect on positioned elements, which are elements with the position property set to anything other than static. For example: relative, absolute, fixed, or sticky. <a href="https://css-tricks.com/almanac/properties/t/top-right-bottom-left/#:~:text=The%20top%20%2C%20bottom%20%2C%20left%20%2C,absolute%20%2C%20fixed%20%2C%20or%20sticky%20.">This  page </a>explains it very well <br><br>
   <img src="https://global.discourse-cdn.com/freecodecamp/original/4X/5/3/c/53c353a673f44fe80ba8c81977940ca97971a172.png" width=500>
