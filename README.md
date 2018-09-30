# Code from udacity course ES6

#### Table of content

- Syntax
    - [Let & const](https://github.com/debiff/es6_course#Let-&-Const)


## Let-&-Const 
There are now two new ways to declare variables in JavaScript: ```let``` and ```const```.

#### Hoisting
Hoisting is a result of how JavaScript is interpreted by your browser. 

Essentially, before any JavaScript code is executed, all variables are "hoisted", which means they're raised to the top 
of the function scope.

#### Why let & const
Variables declared with ```let``` and ```const``` eliminate this specific issue of hoisting because they’re scoped to the block, 
not to the function.

If a variable is declared using ```let``` or ```const``` inside a block of code, then the variable 
is stuck in what is known as the temporal dead zone until the variable’s declaration is processed. 

This behavior prevents variables from being accessed only until after they’ve been declared.

#### Rules for using let and const

```let``` and ```const``` also have some other interesting properties:

- Variables declared with ```let``` can be reassigned, but can’t be redeclared in the same scope.
- Variables declared with ```const``` must be assigned an initial value, but can’t be redeclared in the same scope, 
and can’t be reassigned.