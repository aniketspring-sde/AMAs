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
## Q8. What is the syntax of the <img> tag in HTML?
- ```<img src="image.jpg" alt="Description of image">```
## Q9. What is the difference between WHERE and HAVING?
- WHERE filters individual rows before grouping or aggregation.
- HAVING filters groups after GROUP BY and aggregation.
## Q10. What is the difference between display: none and visibility: hidden?
- display: none, completely removes the element from the page's layout.
- visibility: hidden, makes the element invisible but keeps its space in the layout.
## Q11. How can you view the tables in a database using psql?
- \dt
## Q12. How many rem is 100px?
- 6.25 rem, 1rem=16px
## Q13. What are the different types of CSS units?
- CSS units are mainly divided into two categories:
    
    ### 1. Absolute Units
    
    Absolute units have a fixed size.
    
    - `px` — Pixels
    - `pt` — Points
    - `pc` — Picas
    - `cm` — Centimeters
    - `mm` — Millimeters
    - `in` — Inches
    ### 1. Relative Units
    
    Absolute units have a fixed size.
    
    - `em` — Relative to the font size of the element
    - `rem` — Relative to the root (html) font size
    - `ch` — Relative to the width of the 0 character
    - `ex` — Relative to the x-height of the font
    - `vw` — 1% of the viewport width
    - `vh` — 1% of the viewport height
    - `vmin` — 1% of the smaller viewport dimension
    - `vmax` — 1% of the larger viewport dimension
