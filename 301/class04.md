# 301 class 04 notes

**Why this matters**: This information matters because 

------------------------------------

## React Docs - Forms

Source: [https://reactjs.org/docs/forms.html](https://reactjs.org/docs/forms.html)

**1. What is a ‘Controlled Component’?**

A controlled component is an input form element whose value is controlled by React.

**2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

We should store the users responses when they submit the form because handleChange will run with every keystroke and update the state, so the displayed value will also update as a user enters information.


**3. How do we target what the user is entering if we have an event handler on an input field?**

By adding a name attribute to each element, the handler function can then choose what to do with multiple `input` elements based on the value of `event.target.name`.

----------------------------

## The Conditional (ternary) Operator Explained

Source: [https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

**1. Why would we use a ternary operator?**

We use ternary operators to condense if statements into one line of code.

**2. Rewrite the following statement using a ternary statement:**
`if(x===y){
  console.log(true);
} else {
  console.log(false);`


x===y ? console.log(true) : console.log(false)


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!