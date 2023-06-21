# 401 class 07 notes

**Why this matters**: This information matters because it covers variable scope and global and nonlocal keywords

------------------------------------


**1. Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.**

Scope determines the visibility of a variable within the code; scope of a name or variable depends on where that variable is placed in the code.

Global scope includes the names that are available to all of the code, and local scope includes the names that are only available or visible to the code within the scope.

[Source](https://realpython.com/python-scope-legb-rule/#the-global-statement)


**2. How do the global and nonlocal keywords work in Python, and in what situations might you use them?**

Nonlocal statements consist of the nonlocal keyword followed by one or more names separated by commas; the names refer to the same names in the enclosing Python scope.

Global statements consist of the global keyword followed byone or more names separated by commas; the names listed will be mapped to the global or module scope in which you define them.\


[Source](https://realpython.com/python-scope-legb-rule/#the-global-statement)

**3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.**

Big 0 notation is important because it's a way to measure and compare how efficient a given algorithm is, or theoretically could be. It conceptualizes the "worst-case theoretical running time complexitiies of algorithms for performance analysis."

[Source](https://www.geeksforgeeks.org/analysis-algorithms-big-o-analysis/)

**4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.**

You could simulate a single die roll by generating a random number from 1 to 6 using `random.randint(1,6))`.

[Source](https://artofproblemsolving.com/wiki/index.php/Basic_Programming_With_Python#Program_Example_1_3)

To calculate the probability of rolling a specific number, you could simulate the dice rolls and count the number of times the target number is rolled. So set the count to 0 then set a for loop where `if roll == target number:`, count goes up `count += 1`. 

[Source](https://www.jeffastor.com/blog/using-python-to-calculate-dice-statistics)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!