# 401 class 02 notes

**Why this matters**: This information matters because it explains more foundational elements of Python coding, including TDD, the name/main gate, recursion and recursive functions, and modules and packages.

------------------------------------

**What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?**

Think about the tests first and add first before adding functionality to code. Add tests, fail the tests, write code, run more tests, then refactor, and repeat.

[Source](https://www.xenonstack.com/blog/test-driven-development-python#:~:text=TDD%20is%20nothing%20but%20the,write%20a%20test%20for%20that.)

[Source](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)

**Explain the purpose of the if __name__ == '__main__': statement in Python scripts. What are some use cases for including this conditional in your code?**

Because Python interpreter reads source files and defines variables before executing the code, if it's running the source file as the main program, it will set the name variable to have the value "main." If the file is imported from another module, name is set to the module's name, and then made available as a value to name as a global variable. 

-------------

For example, when developing script designed to be used as module that will be imported to other files, using the name / main will have the following advantages (as opposed to commenting out the call):

* Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
* If you import this script as a module in another script, the __name__ is set to the name of the script/module.
* Python files can act as either reusable modules, or as standalone programs.
* if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.

[Source](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)

**Describe the concept of recursion in Python.**

A function is recursive if it calls itself directly or indirectly. The process is called recursion and the function is a recursive function.

[Source](https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)

**What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.**

Modules and packages facilitate modular programming. Modules are separate smaller, more manageable subtasks within a large programming task that can then be put together to create a larger application. Packages are a way of grouping and organizing modules  via a heirarchical structuring of the module namespace using dot notation. In the same way modules avoid collisions between global variable names, packages avoid collisions between module names. 

Modules can be written in Python, in C and loaded dynamically at run-time, or built-in, and are created by creating a file with Python coding that has a .py extension. Modules are then accessed through an import statement "import + py file name", assuming the module is in the correct directory.

[Source](https://realpython.com/python-modules-packages/)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!
