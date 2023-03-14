# 301 class 02 notes

**Why this matters**: This information matters because it explains important introductory components to React. 

------------------------------------

## React Lifecycle

Source: [https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

**1. Based off the diagram, what happens first, the `render` or the `componentDidMount`?**

The `render` comes before the `componentDidMount`.

**2. What is the very first thing to happen in the lifecycle of React?**

`Constructor` is the first thing that happens, during `Mounting`, which is the first of the three phases.

**3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`**

`Constructor`, `render`, `React Updates`, `componentDidMount`, `componentWillunmount`

**4. What does `componentDidMount` do?**

It's invoked immediately after a component is mounted in order to load anything using a network request or to initialize the DOM. This is a good place to set up subscriptions. setState() can be caused here, but will cause a rerender. 

----------------------------

## React State vs Props

Source: [https://www.youtube.com/watch?v=IYvD9oBCuJI](https://www.youtube.com/watch?v=IYvD9oBCuJI)

**1. What types of things can you pass in the props?**

Things the components store like a the initial number of a counter; in a display with title and subtitle, both title and subtitle can be passed. Things like text that won't change or update and doesn't need state.


**2. What is the big difference between props and state?**

Props is passed into a component and handled outside of the component, and state is handled inside the component.

**3 When do we re-render our application?**

When the user does something; when input changes; when the state is changed inside of the application.

**4. What are some examples of things that we could store in state?**

- Information that will change or update like the information inside of a form - to store what the user changes the form values to, or a counter with numbers that update as the count grows based on user input.
- Data handled within the component alone, ex. in a parent.

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!