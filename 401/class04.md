# 401 class 04 notes

**Why this matters**: This information matters because it gives us more information about foundational Python concepts of classes/objects, more in depth coverage of recursion, and Pytest fixtures and coverage in testing.

------------------------------------


**What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?**

Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are like a template to create your objects.

[Source](https://www.learnpython.org/en/Classes_and_Objects)


**Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?**

A recursive function is a function defined in terms of itself via self-referential expressions, meaning that the function will continue to call itself and repeat its behavior until some condition is met to return a result. It can be useful in situations when a task can be naturally split into several tasks of the same kind, but simpler. Or when a task can be simplified into an easy action plus a simpler variant of the same task.

Things to consider when implementing a recursive funciton are:

- Maintaining state via threading state throgh each recursive call or keeping state in global scope.
- Cache results for efficiency.
- Avoid stack overflow by using fewer stack frames than the default call stack depth

[Source](https://realpython.com/python-thinking-recursively/)
[Source](https://javascript.info/recursion#:~:text=Recursion%20is%20a%20programming%20pattern,variant%20of%20the%20same%20task.)

**What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.**

Fixtures make it so that you can have some objects available to all of your tests, including objects with data you want to share across tests or involving the network or filesystem.

Code coverage allows you to check that your tests have run all of the code, covering the ways that functions could get other results/exceptions that a test previously  didn't check for. 

They improve quality and maintainability of a project by having key testing objects globally available and covering multiple results a piece of code may produce.


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!