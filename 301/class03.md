# 301 class 03 notes

**Why this matters**: This information matters because c

------------------------------------

## React Docs - lists and keys

Source: [https://reactjs.org/docs/lists-and-keys.html](https://reactjs.org/docs/lists-and-keys.html)

**1. What does .map() return?**

In the example given in the source, it returns a new array of numbers with doubled value, since the number was multiplied by two.

Generally though, it creates a new array with the results of whatever method or function you're calling on every element in the calling array.

**2, If I want to loop through an array and display each value in JSX, how do I do that in React?**

Using map() to loop through the array and curly braces {} to be used as JSX.

**3. Each list item needs a unique ____.**

key

**4. What is the purpose of a key?**

Keys help React identify which items have changed, are added, or are removed.

----------------------------

## The Spread Operator

Source: [https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

**1. What is the spread operator?**

Spread is used to expnd an iterable object into a list of arguments.

**2. List 4 things that the spread operator can do.**

- Adding items to arrays
- Combining arrays or objects
- Spreading an array out into a function's arguments
- Using Math functions

**3. Give an example of using the spread operator to combine two arrays.**

From the above source - here the spread syntax combines two arrays, fruits and moreFruits: 

`const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍`

**4. Give an example of using the spread operator to add a new item to an array.**

From the above source - here the spread syntax adds the items in the array fewFruit to the existing fewMoreFruit list.

`const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]`



**5 Give an example of using the spread operator to combine two objects into one.**

From the above source - here the spread syntax combines the properties and methods on objects One and Two into a new object, objectThree: 

`const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂`

----------------------------

## How to Pass Functions Between Components

Source: [https://www.youtube.com/watch?v=c05OL7XbwXU](https://www.youtube.com/watch?v=c05OL7XbwXU)

**1. In the video, what is the first step that the developer does to pass functions between components?**

The developer creates a function called increment where the state that will be changed is located (directly after the parent).

**2. In your own words, what does the increment function do?**

The increment function is passed in a person object, loops through the array of people using map() and finds the one that needs to be updated. The count will increase based on the name that's passed in to this function,  it returns the altered version of the object in the function's variable (ppl) and will then update the state by calling this.setState.

**3. How can you pass a method from a parent component into a child component?**

By creating a prop that refers to that method. In the example, increment = {this.increment} is used to reference the previously created increment function/method.

**4. How does the child component invoke a method that was passed to it from a parent component?**


By calling the method that exists on the parent. In the example, the dev moves from app.js to person.js and adds in the method call inside of the increment method on person.js. The example method call is this.props.increment(this.props.name).

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!