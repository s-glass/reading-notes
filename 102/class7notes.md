
# Class 7 Notes #

## Control Flow ##

Source: [https://developer.mozilla.org/en-US/docs/Glossary/Control_flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

* **Control flow** is the order in which the computer executes statements in a script, typically from the first line to the last line. 
* Control structures like conditionals and loops can change control flow. 
* **Conditional structure** is if...else
* Script can also be set to execute when events occur.
* **Control flow** means that when you read a script, you need to not only read from stat to finish, but look at progra structure and how it affects order of executiuon.

## JS Functions ##

Source: [https://www.w3schools.com/js/js_functions.asp](https://www.w3schools.com/js/js_functions.asp)

* A JavaScript **function** is a block of code designed to perform a specific task; it's executed when "something" invokes it. 

Example: 
' // Function to compute the product of p1 and p2
function myFunction(p1, p2) {
    return p1 * p2;
}'

### Function Syntax ###
* A JS **funciton** is defined wiht the 'function' keyword, followed by a 'name', followed by parentheses '()'
* funciton names can contain letters, digits, _ and $
* the parenthesis may include parameter names separated by commas: ex. (parameter1, parameter2,...)
* the code to be executed by the function is placed in curly brackets {}

Example:
' function name (parameter1, parameter2, parameter3) {
    // code to be executed
}'

* Function **parameters** are listed inside the parentheses () in the function definition.
* Function **arguments** are the **values** received by the function when it's invoked. 
* When inside a function, arguments (parameters) act as local variables.


### Function Invocation ###
* the code inside the function will execute when "something" **invokes** the function:
1. when an event occurs (ex. user clicks button)
2. When it's invoked from JS code
3. Automatically (i.e. self invoked)

### Function Return ###
* When JS gets to a **return** statement, the function stops executing
* If the function was invoked from a statement, JS will "return" to execute the code after invoking the statement.
* Functions often compute a **return** value - which is "returned" back to the "caller." 

Example:
'let x = myFunction (4, 3);  // Function is called, return value will end up in x

function myFunction(a b) {
    return a * b;           // Function returns the product of a and b
}'

The result in this case is 12

### Why Functions ## 
1. It allows you to reuse code - define it once and use it many times
2. It allows you to use the same code many times with different arguments, and to produce different results


### The () Operator Invokes the Function ###
* accessing a function without () will return the function object instead of the function result.

Example:
'function toCelsius(fahrenheit) {
    return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCensius'

### Functions Used As Variable Values ###
* Functions can be used the same was as variables, and in all types of formulas/assignments/calculations. 

Example:
Instead of using a variable to store the return value of a function:
'let x = toCensius(77);
let text = "The temperature is " + x + " Celsius";'

Use the function directly as a variable value:
'let text = "The temperature is " + toCelsius(77) + " Celsius";'

### Local Variables ###
* Variables declared in a JS function become **local** to the function.
* Local variables can only be accessed from within the function. 

Example: 
' // code here can NOT use carName

function myFunction() {
    let carName = "Volvo";
    // code here CAN use carName
}

// code here can NOT use carName'

* Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.
* Local variables are created when a function starts, and deleted when a function is completed.


----------------------------------

## JS Operators ##

Source: [https://www.w3schools.com/js/js_operators.asp](https://www.w3schools.com/js/js_operators.asp)

* 