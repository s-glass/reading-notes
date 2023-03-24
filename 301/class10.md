# 301 class 10 notes

**Why this matters**: This information matters because it outlines the call stack and terminology needed to understand it, along with a rundown of various types of errors and debugging methods.

------------------------------------

## Understanding the JavaScript Call Stack

Source: [https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

**1. What is a ‘call’?**

Function invocation.

**2. How many ‘calls’ can happen at once?**

One at a time, from top to bottom.

**3. What does LIFO mean?** 

Last In, First Out, the principle used by call stack data structures to temporarily store and manage function invocation.

**4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**

`function firstFunction(){
  throw new Error('Stack Trace Error`);
}
function secondFunction(){
  first function();
}
function thirdFunction(){
  secondFunction;
}
thirdFunction();`


**5. What causes a Stack Overflow?**

A stack overflow occurs when there's a function that calls itself (a recursive function) without an exit point. The browser has a maximum stack call that it can accommodate before throwing a stack error.


----------------------------

## JavaScript error messages

Source: [https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

**1. What is a ‘reference error’?**

When you try to use a variable that is not yet declared.

**2. What is a ‘syntax error’?**

When you have something that cannot be parsed in terms of syntax. 

**3. What is a ‘range error’?**

When you try to manipulate an object with some kind of length and give it an invalid length. For example, an array cannot have a negative length.

**4. What is a ‘type error’?**

When the types (number, string, etc.) you are try9in gto use or access are incompatible, like accessing a property in an undefined type of variable.

**5. What is a breakpoint?**

It's an internal stopping or pausing place in a program that allows the developer to find where bugs exist in the code. [Source](https://en.wikipedia.org/wiki/Breakpoint)

**6. What does the word ‘debugger’ do in your code?**

Adds a breakpoint.

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!