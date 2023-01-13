
# class 8 notes #

## Expressions and Operators ##

Source: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

### Comparison Operators ###
* A comparison operator compares its **operands** and returns a logical value based on whether the comparison is true.
* Operands can be numerical, string, logical, or object values. 
* **Strings** are compared based on standard lexico. ordering using Unicode values.
    - if they're not the same type, JS tries to convert them to an appropriate type for the comparison; which usually results in comparing the operands numerically. 
    - exceptions to type conversion within comparisons involve the '===' and '!==' operators, which are strict equality and inequality comparisons. 
    - these operators dont' try to convert the operands to compatible types before checking equality. 
* Examples of Operators:
1. Equal ==
2. Not equal !=
3. Strict equal ===
4. Strict not equal !==
5. Greater than >
6. Greater than or equal >=
7. Less than <
8. Less than or equal <=>

### Assignment Operators ###
*  Assignment operators assign value to its **left operand** based on the value of its **right operand**
* The simple assignment operator is Equal =, ex. x = f() is an assignment expressino that assigns the value of f() to x. 

Examples of compound assignment operators:
1. assignment: x = f()
2. addition assignment: x += f()
3. subtractiuon assignment x -= f()
4. multiplicaiton assignment x *= f()
5. division assignment x /= f()

**Assigning to properties**
* If an expression evaluates to an **object**, then left-hand side of an assignment expression can make assignments to properties of that expression. 

Example:
'const obj = {};

obj.x = 3;
console.log(obj.x); // Prints 3.
console.log(obj); // Prints { x: 3 }.

const key = "y";
obj [key] = 5;
console.log(obj[key]); // Prints 5.
console.log(obj); // Prints { x: 3, y: 5}'

* If an expression doesn't evaluate to an object, then assignments to properties of that expression don't assign.
* It's an error to assign values to unmodifiable properties or to properties of an expression without properties 'null' or 'undefined').

**Destructuring**
* For more complex assignments, the *destructuring assignment* syntax is a JS expression that makes it possible to extract data from arrays/objects using a syntax that mirrors the way array and object literals are constructed.

**Evaluation and Nesting**
* Usually, assignments are used within a variable declaration (for example, with 'const', 'let', or 'var'), or as standalone statements.
* Assignment expressions like 'x = f()' though, will evaluate into a result value that can be used by another expression. 
* By chaining or nesting an assignment expression, the result can be assigned to another variable; logged; put inside an array literal or function call; etc.
* When chaining expressions without () or other grouping operators, the assignment expressions will be **grouped R to L**, but **evaluated L to R**.

**Avoid Assignment Chains**
* Chaining/nesting asisgnments in other expressions can create problems, so it's discouraged. 

-----------------------------------------------
## Loops ##

Source: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#for_statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#for_statement)

### For Statement ###
* A 'for' loop repeats until a specified condition evaluates to **false**. 

Example:
' for ([initialExpression]; [conditionExpression]; [incrementExpression])
statement'

* When a 'for'loop executes, the following happens:
1.Initial expression is executed
2. Condition expresison is evaluated. If true, loop executes; otherwise it terminates.
3. Statement executes
4. If present, incrementExpression is executed
5. Control returns to step 2 

### While Statement ###
* A while statement executes its statements as long as a specified condition evaluates to 'true.' 

Example:
'while (condition)
    statement'

* If the condition becomes false, the statement stops executing and control goes to the statement that follows the loop.
* The conditiuon test occurs before the **statement** is executed - if it returns **true,** the **statement** is executed and the **condition** is tested again. If condition is **false,** execution stops, control goes to statement following **while**.


## Things I Want To Know More About ##
Nothing at this time

URL: [https://s-glass.github.io/reading-notes/102/class8notes](https://s-glass.github.io/reading-notes/102/class8notes)

