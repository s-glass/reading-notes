# 401 class 08 notes

**Why this matters**: This information matters because it introduces list comprehension and decorators, which will be important to upcoming assignments.

------------------------------------

**1. What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.**

my_new_list = [ expression for item in list ]

where the first part is the expression you want to carry out, the second is the object (item) the expression will work on, and the last is an iterable list of objects to build the new list from.

It differs from a for loop in that it's a more elegant, compact, flexible, and faster way of creating lists.

`squares = [x**2 for x in range(10)]

print(squares)`

[Source](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

**2. What is a decorator in Python?**

Decorators are functions that take another function and extend the behavior of the latter function without explicitly modifying it. They provide a simple syntax for calling higher-order functions.

[Source](https://realpython.com/primer-on-python-decorators/)

**3. Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.**

Decorators wrap a function, modifying its behavior. They're commonly used for timing functions, debugging code, slowing down code (to rate-limit a function that continuously checks whether a resource has changed), registering plugins, and to see if a user is logged in.

`def my_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

def say_whee():
    print("Whee!")

say_whee = my_decorator(say_whee)`

[Source](https://realpython.com/primer-on-python-decorators/#a-few-real-world-examples)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!