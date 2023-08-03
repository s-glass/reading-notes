# 401 class 39 notes

**Why this matters**: This information matters because being able to use Django and React together are good skills to sharpen.

------------------------------------

**1. What is React Context, and how does it help in managing state and data sharing in a React application?**

React Context is a React feature that allows users to pass down and consume data in whatever component is needed without having to use props. It helps address state and data sharing by simplifying the state process in avoiding props and props drilling.

[Source](https://www.youtube.com/watch?v=5LrDIWkK_Bc)

**2. Explain the useContext Hook and how it can be used to access data from a React Context within a functional component.**
The `useContext` hook is a simple way to access the context data directly wihtin funcitonal componenets. It is a built-in React hook that allows functional componenets to consume data from a React Context without having to use the `Consumer` component.

It can be used to access data by passing the context you want to access as an argument to the hook. The return will give you the current value of the context, which you can then use in youro component. In order to do this, however, you need to first make sure that the context is provided at a higher component tree level using `MyContext.Provider` so the context can be found and it's value retrieved. 

[Source](https://www.freecodecamp.org/news/react-context-for-beginners/)


**3. Describe the purpose of Next.js, and provide an example from the Vercel Next.js Examples reading on how it can be used to build a scalable web application.**


[Source](https://nextjs.org/learn/basics/create-nextjs-app)
[Source](https://www.youtube.com/watch?v=rtgbaKBhdkk)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!