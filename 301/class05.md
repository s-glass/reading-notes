# 301 class 05 notes

**Why this matters**: This information matters because it details some good planning information and techniques via the content in 'thinking in react', and it gives us some context and vocabulary to situate many of the functions we have recently learned as 'highter-order functions.'

------------------------------------

## React Docs - Thinking In React

Source: [https://react.dev/learn/thinking-in-react](https://react.dev/learn/thinking-in-react)

**1. What is the `single responsibility principle` and how does it apply to components?**

It's a techninque that says that a componenet should ideally only do one thing, and if it ends up growing, should be decomposed into smaller subcomponents.

**2. What does it mean to build a ‘static’ version of your application?**

In step 2 of implementing a UI in React, building a static version means building a version that renders the UI from your data model without adding interactivity yet.

**3. Once you have a static application, what do you need to add?**

UI interactivity via state to be able to change the underlying data model.

**4. What are the three questions you can ask to determine if something is state?**

1. Does it remain unchanged over time? If so, it's not state.

2. Is it passed in from a parent via props? If so, it's not state.

3. Can you compute it based on existing state or props in your components? If so, it's not state.

**5. How can you identify where state needs to live?**

By identifying which component is responsible for changing the state, or 'owns' the state.

The reading details a three step approach to use with every piece of state in your application: 

 - 1. Identify every component that renders something based on that state.
- 2. Find their closest common parent component—a component above them all in the hierarchy.
- 3. Decide where the state should live:
      - Often, you can put the state directly into their common parent.
      - You can also put the state into some component above their common parent.
      - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.


----------------------------

## Higher-Order Functions

Source: [https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

**1. What is a “higher-order function”?**

Higher-order functions are functions that operate on other functions, either by taking them as arguments or by returning them. They allow us to abstract over actions, not just values.

**2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?**

Line two says that the greaterThan funciton should return value 'm' as long as 'm' is greater than the given value 'n'.

**3. Explain how either `map` or `reduce` operates, with regards to higher-order functions.**

Reduce combines all the elements of an array into a single value. It's a higher-order function because it is able to pass it's function values to other functions.

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!