# 201 class 4 notes

**Why this matters**: This information matters because it includes important information about accessibility in web development.

------------------------------------

## Learn HTML

Source: [https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)


Source:

**1. To create a basic link, we wrap text or other content inside what element?**

An `<a>` element

**2. The `href` attribute contains what information?**

It contains the web address

**3. What are some ways we can ensure links on our pages are accessible to all readers?**

- By putting the link title in the regular text versus mouse hover.
- By including keywords in your link text to describe what's being linked to.
- By having descriptive link text for visual readers.
- Don't repeat the URL as part of the link text (don't look nice and sound bad with screen readers.)
- Don't say "link" or "links to" in the link text.
- Keep link text as short as possible.
- Try not to have multiple copies of the same text linked to different places.

---------------------------------------

## CSS Layout

Source: [https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

Source:[https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

**1. What is meant by “normal flow”?**

The way that webpage elements lay themselves out if you haven't changed their layout. The system by which elements are placed inside the browser's viewport.

**2. What are a few differences between block-level and inline elements?**

- Block level element content fills the inline space of the parent element containing it and the element grows along the block dimension to accomodate its content, whereas the size of inline elements is the size of the content (you can't set width or height except for images).

- Block level elements are laid out in the block flow direction, based on the parent's writing mode, while inline elements don't appear on new lines - they sit on the same line along with any adjacent or wrapped text as long as there's space to do so. If there's no space, then the overflow content moves down to a new line.

**3. ___ positioning is the default for every html element.**

Static positioning.

**4. Name a few advantages to using absolute positioning on an element.**

- You can create isolated UI features that don't interfere with the layout of other elements because the gap where the positioned element should be in the document flow is no longer there (an absolutely positioned element no longer exists in the normal document flow).

- Top, bottom, left and right behave differently with absolute positioning - they specify the distance the element should be from each of the containing element's sides versus positioning the element based on its relative position within the normal document flow.

**5. What is a key difference between fixed positioning and absolute positioning?**

- Absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), and fixed positioning usually fixes an element in place relative to the visible portion of the viewport. This means you can create useful UI items that are fixed in place.

---------------------------------------

## Learn JS

Source: [https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

**1. Describe the difference between a function declaration and a function invocation.**

Declaration defines the function and invocation tells the function what to do or states what's happening to it. 

To use a function after it's been declared, you have to invoke it by including the name of the function in the code somewhere, followed by parentheses.


**2. What is the difference between a parameter and an argument?**

Parameters are sometimes called arguments, properties, or even attributes. So there's no difference.

----------------------------------------

## Miscellaneous

Source:[https://www.codefellows.org/blog/6-reasons-for-pair-programming/](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

**1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.**

- Learning from fellow students: I think this benefit will help me be able to see different approaches and perspectives to solving problems. I like learning how someone else uses a different technique to approach an issue, and I think it will help me to be a better and more well-rounded developer.

- Job interview readiness. Being able to practice pair programming ahead of time will be helpful when it's time to do so in job interviews. Having that familarity with the proess and the communication abilities in place will allow me to be able to complete tasks well with lots of different types of people. 


---------------------------------------

### Things I Want To Know More About:
Why is a boolean called a boolean? (to get to the other side?)

Reflection: as a language teacher, I think it's interesting to note that, like with typical language learning, my receptive skills (reading and listening) are currently stronger than my productive skills (speaking and writing)- which is usually what happens in foreign language learning.

