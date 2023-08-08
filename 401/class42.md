# 401 class 42 notes

## Pythonisms

**1. What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.**

Dunder methods are double underscore methods; they allow for defining how instances of a given class should behave when interacting with built-in functions and operators.

Dunder methods are automatically called by the Python interpreter when operations involve a class' objects. The way objects are created, compared, added, printed, etc. can be controlled in this way by defining the methods in the class.

```python
class Node:
  def __init__(self, value = None, next = None, left = None, right = None):
    self.next = next
    self.value = value
    self.left = left
    self.right = right
```

[Source](https://dbader.org/blog/python-dunder-methods)

**2. Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() methods, and why are they important for enabling iteration in a class?**

Iterators are objects that represent a stream of data and provide a way to access elements one at a time. The `__iter__()` menthod returns the iterator object and initializes the iteration, `__next__()` returns the next value from the iterator or raises `StopIteration` when there's no more items to be returned.


[Source](https://dbader.org/blog/python-iterators)

**3. What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.**

Generators are functions that allow for iterating concisely and in a more memory-efficient way compared to regular functions.

Generators are different from regular functions primarily in the memory efficiency (regular functions generate lists of values, generators generate values "on the fly" so it doesn't have to hold all values at once); and in execution flow (regular functions go from start to end, generators can be paused and resumed).

[Source](https://dbader.org/blog/python-generators) and chat GPT for clarification.

**4. Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.**

Decorators allow for modifying or extending the behavior of functions/methods without having to change the code. They take another function as input, perform some action either before or after the input function is executed, and then return a modified version of the input function.

[Source](https://realpython.com/primer-on-python-decorators/)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!