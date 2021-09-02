## introduction-to-html
### HTML Anatomy
- An Opening tag
- The Content ("Hello World!" text)
- An Closing tag
### The body
```html
<body>
  <p>"Life is very short and what we have to do must be done in the now."
  - Audre Lorde</p>
</body>
```
### HTML Structure
```html
<div>
  <p>This paragraph is a child of the div element and a grandchild of the body element</p>
</div>
```
### Headings
The following is the list of heading elements available in HTML. They are ordered from largest to smallest in size.
- h1 -used for main headings. All other smaller headings are used for subheadings.
- h2 , h3, h4 ...
```html
<h1>BREAKING NEWS</h1>
```
### Divs
- One of the most popular elements in HTML is the div element. 
- div is short for “division” or a container that divides the page into sections.
- divs don’t inherently have a visual representation, but they are very useful when we want to apply custom styles to our HTML elements.
  <h1>The Brown Bear</h1>
  <div>
    <h2>About Brown Bears</h2>
    <h3>Species</h3>
    <h3>Features</h3>
  </div>
  <div>
    <h2>Habitat</h2>
    <h3>Countries with Large Brown Bear Populations</h3>
    <h3>Countries with Small Brown Bear Populations</h3>
  </div>
  <div>
    <h2>Media</h2>
  </div>
### Attributes
- The name of the attribute
- The value of the attribute
```html
<div id="introduction">
    <h2>About Brown Bears</h2>
    <h3>Species</h3>
    <h3>Features</h3>
</div>
```
### Displaying Text
```html
<div>
  <p><span>Self-driving cars</span> are anticipated to replace up to 2 million jobs over the next two decades.</p>
</div>
```
It’s best to use a <span> element when you want to target a specific piece of content that is inline, or on the same line as other text.
