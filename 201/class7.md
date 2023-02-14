# 201 class 7 notes

**Why this matters**: This information matters because it introduces object syntax in JS, give us information about the Document Object Model (DOM), and includes articles on immutable and mutable data in JS.

------------------------------------

## Domain Modeling

Source: [https://github.com/codefellows/domain_modeling#domain-modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

**1. Explain why we need domain modeling.**

From the source above: "A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams."


------------------------

## HTML Table Basics

Source: [https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

**1. Why should tables not be used for page layouts?**

- They reduce accessibility for visually impared users

- They produce "tag soup," making the code harder to write, maintain, and debug.

- They aren't automatically responsive (where width defaults to 100% of parent elements). Instead, they are sized by default.


**2. List and describe 3 different semantic HTML elements used in an HTML <table>.**

- `<td>` - Table Data - this is the smallest container inside a table.

- `<tr>` - Table Row - this is used to keep a row from growing and starts placing subsequent cells on a new row.

- `<th>` - Table Headers - The cells that go at the start of a row or column.

- `<col>` and `<colgroup>` define the styling information for an entire column of data all in one place.

-----------------------


## Introducing Constructors

Source: [https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

**1. What is a constructor and what are some advantages to using it?**

A constructor is a function called using the `new` keyword. It's a shorter way of defining the "shape" of an object - the set of methods and properties it can have, and then creating as many objects as you want by updating the values for the properties that are different.

**2. How does the term this differ when used in an object literal versus when used in a constructor?**

When using `new` in a constructor, it will create a new object, bind `this` to the new object, run the code in the constructor, and return the new object.

In an object literal, you don't use the word `new` to create a new object. Instead you must invoke the new Object() to create it.


-------------------------

## Object Prototypes Using a Constructor

Source: [https://ui.dev/beginners-guide-to-javascript-prototype](https://ui.dev/beginners-guide-to-javascript-prototype)


**1. Explain prototypes and inheritance via an analogy from your previous work experience. NOTE: This is a very common front end developer interview question.**

According to [this source](https://javascript.info/prototype-inheritance): "When we read a property from object, and it’s missing, JavaScript automatically takes it from the prototype. In programming, this is called “prototypal inheritance”.

So if I want to make an analogy from previous work experience, I could say the following:

let object = supply closet
let property = pens
let prototype = Bob's desk
let JavaScript = me

So in a previous job, I once went to the supply closet to get pens that I need to take with me at an even, and they were missing. So I automatically went to my colleague Bob's desk to find and take pens since he always hoarded them.


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!