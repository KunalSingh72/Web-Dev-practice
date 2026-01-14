## HTML Basic 
- Hyper Text Markup Language
- Responsible for Webpage Structure
- < element> content </ element>

< !DOCTYPE html> == HTML version
< html> == root element
< head> == information about the page (MetaData)
< body> == What will be displayed
< title> == Page title

- Nested elements are called *child elements*
- White spacing collapsing = Html ignore white spaces in code
- Emmet == Don't need to press '<' bracket.
- Internal Links == When referencing to any target in the same page. We have to give *id* of an element in href using '#'
- for special characters we use "&" followed by code or name.


## Good Practice
- use "./image.png" as path instead of "/image.png" OR "image.png"
- Use < ul> elements for forward navigation.
- 

## Keep in mind
- *name* attribute in *radio* type *input* element should match. so they can act as options.
- *value* attribute in *radio* type is the value that actually gets submitted. 

## Elements

< link rel href> = Relationship between current doc and external resource/for linking docs
< script> = defines client-side JavaScripts
< base> = specifies base fo all relative URLs in a page
< h1> to < h6> = Heading
< p> = Paragraph
< img> = image
< br> = line break
< a> = link
< sup> = top element
< sub> = bottom element
< strong> = Bolded text
< em> = Italic
< ul> = unordered list
< ol> = ordered list
< table> = creates table
< th> = table head
< tr> = for table rows
< td> = for table data/columns
< form action> = form element
< input type name placeholder value> = inputting data
< button> = clickable buttons
< label for> = labeling for elements 
< textarea name cols rows checked> = for inputting paragraph like text writing
< select> = Drop down option element
< option> = used with < select> for options

## Attributes

rel -> relationship
src -> source path/link
alt -> alternative syntax
width & height
href -> Hyper text reference
target = "_blank" -> link open in new tab
action = "#address/location" -> where the form data would be sent 
method = "POST" -> how this information is going to be processed
type = "text/number/submit/password/email/radio/checkbox" -> type of the input/output data
name -> identify form elements for data submission
id -> used for labels, selection and identification of the element.
for="#id" -> for which element
placeholder -> shown in place of the value in input element (for general idea)
value -> hardcode data placed in input element OR in place of the 'submit' text in submit button
rows -> rows 
cols -> columns
checked -> automatically checked checkbox


## values

submit -> submits form
password -> shown in dots
email -> requires '@' and '.com'
radio -> tick option selection
checkbox -> used for multiple option selection