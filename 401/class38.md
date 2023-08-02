# 401 class 38 notes

**Why this matters**: This information matters because 

------------------------------------

**1. How does lifting state up in a React application help with managing data flow and what are the benefits of using this approach?**

Lifting up the State: As we know, every component in React has its own state. Because of this sometimes data can be redundant and inconsistent. So, by Lifting up the state we make the state of the parent component as a single source of truth and pass the data of the parent in its children. This way individual components don't manage their own state, but state moving to the closest common ancestor allows data to be shared. The benefits are improved data flow and centralized state management.

[Source](https://legacy.reactjs.org/docs/lifting-state-up.html)
[Source](https://www.geeksforgeeks.org/lifting-state-up-in-reactjs/)
and chatGPT

**2. Explain the concept of conditional rendering in React and provide an example of how to implement it in a component.**


Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them. This way, you can create distinct components that encapsulate behavior you need. Then, you can render only some of them, depending on the state of your application.

As an example, according to the example listed below, when we have these two components:

```python
function UserGreeting(props) {
  return <h1>Welcome back!</h1>;
}

function GuestGreeting(props) {
  return <h1>Please sign up.</h1>;
}
```

We can create a third, greeting component that will display either of the two above depending on if a user is logged in:

```python
function Greeting(props) {
  const isLoggedIn = props.isLoggedIn;
  if (isLoggedIn) {
    return <UserGreeting />;
  }
  return <GuestGreeting />;
}
```

[Source](https://legacy.reactjs.org/docs/conditional-rendering.html)

**3. What are the main principles behind “Thinking in React” and how do they guide the process of designing and building a React application?**

- breaking a user interface into components
- component heirarchy and state management
- one-way data flow
- reusability of components


[Source](https://react.dev/learn/thinking-in-react)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!