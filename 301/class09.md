# 301 class 09 notes

**Why this matters**: This information matters because it details functional programming and introduces Modules and require() in Node.js

------------------------------------

## Functional Programming Concepts

Source: [https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

**1. What is functional programming?**

Functional programming is a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

**2. What is a pure function and how do we know if something is a pure function?**

A pure function is also referred to as deterministic. It returns the same result if given the same arguments and it doesn't cause observable side effects.

**3. What are the benefits of a pure function?**

-The code is easier to test
-No mock needed

**4. What is immutability?** 

Unchanging over time or unable to be changed at all.

**5. What is Referential transparency?**

Referential transparency = pure function + immutable data.

----------------------------

## Node JS Tutorial for Beginners - #6 Modules and require()

Source: [https://www.youtube.com/watch?v=xHLd36QoS4k](https://www.youtube.com/watch?v=xHLd36QoS4k)

**1. What is a module?**

A module is a JS file.

**2. What does the word ‘require’ do?**

Require passes a string in () that's a path to the module that's required in a given file.

**3. How do we bring another module into the file the we are working in?**

In the module file, export what you wan't to be available outside of the module: 

`module.exports = name of things to export;`

In the receiving file, set a variable:

`let variableName = require('file name');`

**4. What do we have to do to make a module available?**

`module.exports = name of things to export;`


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!