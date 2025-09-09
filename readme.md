Answer to  the qustion no ( assignment 06)

#### 1) What is the difference between var, let, and const?
var: function-scoped, can be redeclared, hoisted.
let: block-scoped, can be updated but not redeclared.
const: block-scoped, cannot be reassigned.

#### 2) What is the difference between map(), forEach(), and filter()? 
forEach: runs function for each item, returns nothing.
map: transforms items, returns new array.
filter: selects items that pass condition, returns new array.

#### 3) What are arrow functions in ES6?
Shorter function syntax: () => {}
Lexical this (inherits this from parent scope).

#### 4) How does destructuring assignment work in ES6?
Extract values from arrays/objects into variables.
const [a, b] = [1, 2];
const {name} = {name: "Rafi"};

#### 5) Explain template literals in ES6. How are they different from string concatenation?
Use backticks `...`.
Supports interpolation ${...} and multi-line strings.
Easier than + concatenation. 