# 401 class 03 notes

**Why this matters**: This information matters because handling files (opening/closing/reading) and handling exceptions are both important tools to accessing information and successfully executing Python code.

------------------------------------

**What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?**

It's purpose is to automatically close the file once it leaves the `with` block, even in cases of error. It helps manage resources by making sure that a file opened is never left open after it's been utilized or referenced, leaving it open to resource leaks.

[Source](https://realpython.com/read-write-files-python/)

**Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.**

The `read()` method returns the file content, and the `readline()` method returns one line from the file. 

You could use `read()` when you need to use a file-wide manipulation, like a regex search or substitution.

`readline()` would allow you to parse a single line without having to read the whole file and would be helpful in, for example, reading a file line by line to avoid processing large files that don't fit in memory.

[Source](https://stackoverflow.com/questions/38105507/when-should-i-ever-use-file-read-or-file-readlines)

[Source](https://net-informations.com/python/file/diff.htm)


**Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.**

Exception errors happen when correct code results in an error (versus a syntax error). Exception handling is the process of responding to exceptions in a custom way during the execution of a program.

Try and except statements can be used to handle exeptions by keeping statements that can raise excpetions inside the try clause and writing the statements that handle the exception inside the except clause.

For the example below - the statements that can cause the error are placed inside the try statement (second print statement in our case). The second print statement tries to access the fourth element of the list which is not there and this throws an exception. This exception is then caught by the except statement.

```
a = [1, 2, 3]
try:
    print ("Second element = %d" %(a[1]))
 
    # Throws error since there are only 3 elements in array
    print ("Fourth element = %d" %(a[3]))
 
except:
    print ("An error occurred")
  ```

The keyword `finally` handles exceptions by always being executed after the try and except blocks - including when a try block terminates due to an exception.

For example,
```
try:
    k = 5//0  # raises divide by zero exception.
    print(k)
 
# handles zerodivision exception
except ZeroDivisionError:
    print("Can't divide by zero")
 
finally:
    # this block is always executed
    # regardless of exception generation.
    print('This is always executed')
  ```

[Source](https://www.programiz.com/python-programming/exception-handling)

[Source](https://www.geeksforgeeks.org/python-exception-handling/)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!