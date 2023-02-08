# 201 class 03 notes

**Why this matters**: This information matters because it's an expansion on the basic building blocks for beginning developers, including the basics of HTML, CSS, and JavaScript.

## Learn HTML

Source:[https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

**1. When should you use an unordered list in your HTML document?**

The <ul> element is used when grouping items that don't have a numerical ording and the order has no meaning. 


**2. How do you change the bullet style of unordered list items?**

You can display an unordered list as a bullet of circles, squares, or dots. The bullet style isn't defined in the HTML part of the page, but in the CSS `list-style-type` property. If no CSS `list-style-type` property applies to the element, the bullet type is selected based on the nesting level of the list.

The <type> attribute sets the bullet style for the list, with the values defined as `circle` `disc` and `square.`


**3. When should you use an ordered list vs an unorder list in your HTML document?**

Ordered lists should be used when the order of items in the list is meaningful.


**4. Describe two ways you can change the numbers on list items provided by an ordered list?**

 - Add the boolean attribute `reversed` to the `<ol>` attribute: items will be numbered in reverse order, from high to low.

 - Add the attribute `type` to the `<ol>` attribute: `i` displays lowercase Roman Numerals, `1` displays numbers (default), `a` displays lowercase letters, etc.


---------------------------------------------------

## Learn CSS

Source: [https://developer.mozilla.org/en-US/docs/Learn/CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

Source: [https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)


**1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**

In the story of "The Box Model," Margin and Padding are fraternal twin siblings. Poor Margin has both anxious and avoidant attachment tendencies. Most of the time Margin pushes other elements away from its box, but when Margin is negative, it causes it to overlap completely with the other things that are on the page with it. For this reason, it's best for Margin to not ~~start new relationships~~ be added until after the size of the box is already ~~stable~~ calculated. 

Padding, on the other hand, was perpetually used as a pawn by one of its parents, Border, to push the other parent, Content, away from them. This, as you can imagine, caused some long-term issues deep in Padding's psyche. Regardless of this dynamic, and unlike Margin, Padding is never negative.  

**2. List and describe the four parts of an HTML elements box as referred to by the box model.**

- Margin: The outermost layer, wrapping content, padding, and border as white space between its box and other elements. Sized using `margin`

- Border: Wraps the content and padding. Sized using `border`

- Padding: Sits around the content as white space. Sized using `padding`

- Content: Area where content is displayed. Sized using `inline-size`, `block-size`, `width`, and/or `height`


---------------------------------------------------

## Learn JS

Source: [https://developer.mozilla.org/en-US/docs/Learn/JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

Source: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)


**1. What data types can you store inside of an Array?**

Strings, numbers, objects, and other arrays. You can also mix data types in a single array.

**2. Is the people array listed below a valid JavaScript array?**

No, it's not valid because there are three sets of [ ] brackets within the original set of [ ] brackets (which I think means there's three arrays?).

**If so, how can I access the values stored? If not, why?**

You can access the arrays in their respective groups, but not the items within the arrays individually because they are separated into 3 different [ ] arrays. For example, console.log(people[0]) returns the entire first array: ['pete, 32, 'librarian', null]. 


` const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`


**3. List five shorthand operators for assignment in javascript and describe what they do.** [Source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

- Assignment: `x = f()`,`=`, assigns the value of its right operand to its left operand

- Addition: `x += f()`,`+=`, assigns the value of its left operand to the sum of the right operand.

- Subtraction: `x -= f()`, `-=` assigns the value of its left operand to the difference of the right operand.

- Multiplication: `x *= f()`, `*=` assigns the value of its left operand to the product of the right operand.

- Division: `x /= f()`, `/=` assigns the value of its left operand to the quotient of the right operand.


**4 Read the code below and evaluate the last expression and explain what the result would be and why.**

I don't know the answer, but I'm going to say what I do know. I do know that a is a number, b is a string, and c is a boolean, and when I put this in my repl.it, it produces nothing. 

In a boolean context, a = 10 is falsy, b = 'dog' is truthy, and c = false is falsy.
The only operator we have in the last expression is addition. There are no comparison or logical operators. So all I have for this is (falsy + falsy) + truthy.

 `let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;`


**5. Describe a real world example of when a conditional statement should be used in a JavaScript program.**

In a weather app, when it's morning, displaying a sun, and displaying a moon at night hours. Or showing an image that reflects whatever the weather currently is. 


**6. Give an example of when a Loop is useful in JavaScript.**

When looking through a list of names (the task needs to be done more than once in a row).

----------------------------------------------

### Things I Want To Know More About:
Question #2 in the JS section about arrays because I'm not sure I arrived to the right conclusion.