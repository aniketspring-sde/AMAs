## Q1. What is the difference between inline and block elements?  
### Block Elements        

-  Start on a new line.  
-  Take up the full available width by default.
-  Can contain both block and inline elements (depending on HTML rules).
-  You can set `width` and `height`.
### Inline Elements   
- Stay on the same line as surrounding content.
- Only take up as much width as needed.
- Typically contain text or other inline elements.
- `width` and `height` generally have no effect.
## Q2. What does flex: 1 mean in CSS?
- flex: 1 is a shorthand used on a flex item. It tells the item to grow and take up the available remaining space in a flex container.
## Q3. What are attributes in HTML?
- In HTML, attributes provide additional information or configuration for an HTML element.
## Q4. What is the difference between an element and a tag?
- A tag is a piece of HTML syntax that tells the browser how a particular part of a webpage should be interpreted.
- <p>Hello World</p>, in this, <p></p> these are tag. 
- An HTML element is the complete structure consisting of the opening tag, content, and usually the closing tag.
- <p>Hello World</p> , the entire thing is element.
## Q5. Which clause is used for sorting data in SQL?
- ORDER BY
## Q6. What is difference between align-items and align-content in CSS?
- align-items controls how individual flex items are aligned along the cross axis.
- align-content controls the spacing and positioning of multiple flex lines.
## Q7. What are the different types of pseudo-classes in CSS?
- A pseudo-class in CSS is a keyword added to a selector to specify a special state or condition of an HTML element.
  ## CSS Pseudo-classes

### 1. User Interaction
- `:hover`
- `:active`
- `:focus`
- `:focus-visible`
- `:focus-within`

### 2. Links
- `:link`
- `:visited`

### 3. Form States
- `:checked`
- `:disabled`
- `:enabled`
- `:required`
- `:optional`
- `:valid`
- `:invalid`
- `:read-only`
- `:read-write`
- `:placeholder-shown`

### 4. Child / Structural
- `:first-child`
- `:last-child`
- `:only-child`
- `:nth-child()`
- `:nth-last-child()`

### 5. Type-based
- `:first-of-type`
- `:last-of-type`
- `:only-of-type`
- `:nth-of-type()`
- `:nth-last-of-type()`

### 6. Logical / Selector
- `:not()`
- `:is()`
- `:where()`
- `:has()`

### 7. Document / General
- `:root`
- `:empty`
- `:target`
- `:lang()`
- `:fullscreen`
