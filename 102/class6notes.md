
# Class 6 Notes #

## JavaScript ##

Source:[https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

* What is JavaScript? A lightweight, interpreted, or "just in time" compiled programming language. It is a scripting language that allows you to create dynamically updating content, control multimedia, animate images, and many other things.


--------------------------------

## Intro to JavaScript - basic output ##

Source: [https://code-maven.com/introduction-to-javascript](https://code-maven.com/introduction-to-javascript)

* Where is JS run? Traditionally inside web browsers, but more recently on the server as well (i.e. Node.js)

* There's 3 parts to JS:
1. The language itself
2. The "DOM API" - how it interacts with the various parts of a web page in a browser
3. The server API, provided by Node.js or another server-side system

* Any text editor can be used
* You can either embed the JS code inside the HTML file or put a line in the HTML file including the JS file, by adding '<script></script>
* Examples of how JS displays text as output:
1. 'alert()" - pop-up with text
2. 'document.write' - changes the content of the page; embeds a snippet
3. 'console.log' - way to print debugging info through the JS console

---------------------------------

## JavaScript input with prompt and confirm ##

Source: [https://code-maven.com/javascript-input-with-prompt-and-confirm](https://code-maven.com/javascript-input-with-prompt-and-confirm)

* Ways to receive input with JS:
1. 'prompt()" - shows a pop-up window with text and a textbox a user can fill in
2. 'confirm()' - pop-up that allows developer to ask "yes/no" question; an OK response returns 'true' and cancel or ESC returns 'false'

----------------------------------

## JavaScript Variables ##

Source: [https://www.w3schools.com/js/js_variables.asp](https://www.w3schools.com/js/js_variables.asp)

* Variables are containers for storing data values.
Example: x, y, and z are variables declared with 'var'
'var x = 5;
var y = 6;
var z = x + y;'

* There's 4 ways to declare a JS variable:
1. var (1995 - 2015)
2. let : if you think the value of the variable can change
3. const : if you think the value of the variable can't change
4. (nothing)

### JS Identifiers ###
* All JS **variables** must be identified with **names**, called **identifiers**
    - Can be short names like x or y, or more descriptive like age, sum, totalVolume

* General rules of naming variables:
1. Names can contain letters, digits, _ and $
2. Names must begin with a letter
3. Names can begin with $ and _ 
4. Names are case sensitive
5. Reserved word like JS keywords can't be used

* **The Assignment Operator**: The = is an "assignment" in JS, not an 'equal to' operator, different from algebra

* **JS Data Types**: 1) text values (text strings), and 2) numbers

* **Declaring a JS Variable**: Creating a variable is declaring a variable in JS
 - Declare a variable with 'var' or 'let', after which it has no value (it's undefined)
 - to assign value, use '='
 - you can declare many variables in one statement (separated with comma)
        - Example: 'let person = "John Doe", carName = "Volvo", price = 200;'
- or separate them on multiple lines
        - Example:
        'let person = "John Doe";
        carName = "Volvo";
        price = 200;'

* **Value = undefined** - a variable without a value is 'undefined'
- Example, variable carName will be undefined here:  'let carName;'

* **Re-declaring JS variables** - if you re-declare a variable with 'var', it doesn't lose it's value, however, you cannot re-declare a variable declared with 'let' or 'const'
- Example: 'let carName = "Volvo";
            let carName;'

* **JS Arithmetic** with algebra, you can do arithmetic with JS variables using operations like '=' and '+'
 - If you put a number in quotes, however, the rest of the numbers are treated as strings and concatenated

* **JS Dollar Sign** - The dollar sign is a letter, so identifiers with $ are valid variable names
- not common in JS but sometimes used as an alias for the main function in a JS library

* **JS Underscore _**: underscore is a letter, so identifiers with _ are valid variable names
- not common in JS but sometimes used as an alias for private/hidden variables

-------------------------------

Add to bookmark: [https://www.youtube.com/playlist?list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-](https://www.youtube.com/playlist?list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-)


## Things I Want To Know More About ##

Nothing at this time.

URL: [https://s-glass.github.io/reading-notes/102/class6notes](https://s-glass.github.io/reading-notes/102/class6notes)