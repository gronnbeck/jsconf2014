# JS LvL 9k

Diving in to the VM?

## Primitives
All the primitives (hidden classes): Number, Boolean, Null and Undefined

Primitives can be objects
```js
var x = new Number(123)
var y = 123

// Takk til Big Mike
x instanceof Object // = true
y instanceof Object // = false
```
x and y will treated differently by the VM

## Array and Objects
```js
var foo = [1,2,3,4,5]
var bar = new Array()
```
compile time: foo
runtime: bar


## Hidden Classes
```js
var foo = { x: 13, y: 37 }
var bar = { x: 13, y: 37 }

var qux = { y: 37, x: 13 }
```
foo and bar has the same hidden class, qux is different. WAT?


## Custom Primitives
Implement valueOf and toString (did I get that right?)

## Functions
Something about inheritance of Functions? Did not understand. Maybe look it up later.

instanceOf points to the prototype

## Hoisting and closures
* **Hoisting**: If a variable is not defined inside the current scope. It will try to look for it at the scope above.
* **Closures**: Function closure. For-loops does not provide closures. Closures provide scopes.

<3 Garbage...
---

Rest was about Garbage Collection Algorithms.
