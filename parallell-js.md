# Parallell JS
Jaswanth Sreeram  (Intel)

## Why?
Parallellism everywhere

### Why Parallell JS?
Game, Multimedia etcetc

## Parallell Model for JS
We want a model that is HL that fits JS, and it to be deterministic.


## Three Pillars
1. Arrays and Typed Objects
2. HL Methods
 * buildPar
 * mapPar
 * reducePar
 * etc...
3. Elemental functions
 * Side effect free


```js
 [1,2,3].mapPar(v => v + 1)
```

The HL Methods are documented... somewhere.

## ES7 Proposal
Parallell JS is implemented in FF Nightly.

JIT Support for checking that your program does not do global changes
(parallel safty analysis)

Work-straling schedular: For balancing work
...

## PJS + (GP)GPU
* How do we use the GPUs adr space in JS?
* How do we compile js to DirectX, OpenGL, OpenCL?
  - Something that is possible to express in OpenCL cannot be expressed in OpenGL etc.
* There is no function pointers on the GPU
* Heap alloc (like JS does) is hard to do on the GPU
* The developer must keep track of the different kind of GPU to get good performance

### The idea is to get the browser to to all this (runtime)


### Energy and Performance
Using the GPU lowers the Energy and increases the Performance by a multiple (MM, 2D-Conv, Mandel)
