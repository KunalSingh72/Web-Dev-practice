## CSS

- Responsible for Styling the web 
- HTML => structure, CSS => Layout and Look

selector{
  property: value;
}

3 Types of CSS (Top  to bottom heirarchy):
- Inline CSS (Element specific)
- Internal CSS (Page speicific)
- External CSS (Project Specific)

- /* Comment */
- Elements can have id and class both at the same time. In this case, id attribute will over-write class atribute. 
- Elements inherits the properties of just upper level elements. {body > div > p > span}
- Css follows last rule. In case of overwriting properties, css will be applied which was written in the last.
- Specificity => if any element has specific class or id. it will apply them instead of common attributes.
- * => selects all elements in the project. it has least specificity.
- Fixed values stay same on all screens (pixels) and relative values varies for different screen/parent elements (responsiveness) (percentage/em/rem)
- 1 em/rem = 16px default browser style; Base value;
- *font-stack* = if font doesn't support, browser applies other.
- the third font in font-stack is called *generic font*
- while importing fonts from google fonts. it is set for maximum and minimum font weight. So it won't go outside of them. 
- *Block level* elements have default margin.
- *Outline* can be moved away and inside the element using *outline-offset*, but border can't
- When applying text-align. all inline elements will be centered but block elements will not, only their child text elements will be centered.
- *Inline Elements* needs to be block element for applying padding and margins  

### Selectors

1. Element (Type) Selector {h1, p}
  - Selects all the elements in the project.

2. Id Selector {#submit-btn, #name}
  - should be unique for each element. (works if used multiple times)
  - must match the exact name.

3. Class Selector {.box, .container}
  - when multiple elements use same attributes.

4. Group Selector = selecting multiple elements {h1,h2} 

### Properties

color: text color
text-transform: text manipulation (lowercase, uppercase)
font-weight
font-style
calc => mathematical operations
text-align => alignment in the block
padding => distance between border and content inside
margin => distance between border and content outside
display => element behaviour
opacity => opacity between 0 to 1
visibility => hidden/visible
min-height => even if the content of the element is not big enough, it keeps the size minimum
background: lg, url() bg-p/bg-s bg-r bg-a;
### Value

rgb => red, blue, green
rgba => RGB + alpha (opacity/transparency from 0 to 1)
HEX values => #RRGGBB {123456789 ABCDEF}
pixels (px) => fixed values. same on all devices.
% => responsive values
em => relative depends on parent
rem => relative depends on root 
block => Always starts a new line and takes full width
Inline => Does not start new line and only take up as much as content space 
display: none; => removes the element from html
background-repeat: round; => only repeat when fully fits