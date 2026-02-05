# JavaScript

- Js is a technology that we use to create websites.
- Js makes web interactive.
- giving instructions to a computer => computer follows are instructions.
- we use camelCase, PascalCase, kebab-case and snake_case.
- _Auto-boxing_ automatically wraps the value to make it act as object.

## Syntax

rules that we have to follow when using a programming language

Concatenation => adding two strings together.
Interpolation => `${}`

## Variables

- Any value can be assigned to variables
- Any variable created inside a scope stays in the scope

let => value can be changed in future.
const => value cannot be changed.
var => variables (don't use now because it doesn't follow scope of the variable)

## Conditional

== -> converts both values into same type and checks
=== -> do not change the type
!==

if(condition) => Runs if condition is true
else if(condition) => different condition that might be true
else => Runs only if all the conditions are false.

&& (AND) => true only if both conditions are true
|| (OR) => true if any of the condition is true
! (NOT) => flips the value

false value => values that behaves like false.

- 0
- ''
- NaN (Not a Number)
- undefined (don't have value)
- null

Truthy value => values that behaves like true. (all other are truthy)

Ternary Operator

- true ? 'truthy' : 'false'
- returns value
- shortcut fot if-else

Guard operator
false && value2 => doesn't check value2

Default Operator
true || value2 => doesn't check value2

## Functions

- reusable block of codes
- written once and used again and again by calling

### return

- used for returning a value from a function
- empty return will return undefined
- all the code after return doesn't work in functions

### parameters

- They are used to pass values to funtions.
- passed with function calling.
- A default value can be given to the parameter function(para = default_value)
- Default value only works if null is not passed.

## Objects

- it groups related values together in form of _properties_ and _values_
- **delete object.property** can be used to delete any property
- Best when similar values needs to be grouped and used.
- for accessing the porperty of an object we use:
- it can have variables, functions and objects inside itself.
- all built-in functions in Js are functions inside and objects. [ex: console.log()]
- Objects are just reference in the memory, which allows variable to **copy by reference**
- Any change done by that copy reference. original value also changes.

### Dot notation

- **object.property_name** (dot notation)
- properties can be modified and created
- But throws error if tried to access a property which doesn't exist

### Bracket notation

- object['property']
- doesn't throws error, instead gives _undefined_

### Nested objects

- objects can be created inside an objects
- dot => object.inner_object.property
- dot => object['inner_object']['property']

### Destructering

const msg = obj2.msg; ==> const { msg }= obj2;

### Short hands

```
const obj5 = {
      // msg: msg,
      msg,
      // method: function fun1() {
      //   console.log('method');
      // }
      method() {
        console.log('method');
      }
    };
```

### Built-in Objects

#### JSON

- JavaScript Object Notation
- A syntax
- similar to Js object but has less features
- All the properties and values in JSON must use double quotes ("")
- It doesn't support functions
- More universal than normal objects created in Js
- Used when we send data between computers
- when we store data

**JSON object** are used to convert _javascript_ objects into JSON

#### Local Variable

- permanent data storage
- Used to store data locally on browser
- only supports strings.
- for storing objects, use JSON.stringify()
- if something doesn't exist, it returns null.

## Built-in properties & methods

typeof # => tells type of input
alert() => used for alert popup on page
console.log() => displaying in console
string_value.length => returns length of the string
string_value.toUpperCase() => returns the copy of string by uppercasing all the characters
string_value.length => returns length of the string
string_value.length => returns length of the string

## Event Listeners
onclick => used for running code in html doc. (inline)
onkeydown => used for key pressing features in html doc. (inline)
onscroll => scrolling
onmouseenter => hovering over
onmouseleave => stop hovering over

### Built-in for Objects

JSON.stringify(object_name) => convert js object into string (exclude functions)
JSON.parse(JSON_string) => convert string into js object
localStorage.setItem(property_string, value_string) => stores data locally
localStorage.getItem(property_string) =>

## DOM

- Document Object represents/models the webpage
- Document Object Model
- Built-in Object
- DOM is used to change something on the web page.
- DOM combines Js and Html together
- Any html element inside Js would be converted into object 

## Window
- Window object represents browser window
- don't need to write window, Js automatically does that

### DOM properties

document.title -> Title of the page
document.body -> selects the body of the webpage
document.body.innerHTML -> all the html of the body
document.querySelector -> let us get any element from the html page. (only first element will be selecter if html element is selected directly)
document.quesrySelector.innerText -> selects all the text inside an element. (if innerHTML don't work due to spaces)
document.querySelector.value -> always be a string value
document.querySelector.classList -> gives us control of the class attribute
## Math

Math.round() => rounds to nearest whole number.
Math.random => generates number between 0 & 1 (0<= n < 1)
