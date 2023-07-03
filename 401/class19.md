# 401 class 19 notes

**Why this matters**: This information matters because regex allows devs to check whether a pattern exists in a given text, and shutil allows for high level file operations.

------------------------------------

**1. How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary library to work with them?**

A specific sequence of characters in a regular expression is used to check for patterns in a string. The primary library used to work with regex is `re`.

**2. What is the purpose of the shutil library in Python, and provide an example of a common use case for file or directory management with this library?**

The shutil module is used for high-level file operations like copying and archiving. For example `copyfile()` copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.

[Source](https://pymotw.com/3/shutil/)

**3. Explain one automation idea from the assigned material and describe how it can be implemented using Python’s regular expressions and shutil libraries.**

File copying - copying a file from one location to another.

With regex: name the pattern and then use this script:
```python
for filename in file_list:
    if re.search(pattern, filename):
      # copy the file
```

With shutil: iterate over the files and check extensions, then use the `shutil.copy()` function:

```python
for filename in file_list:
    if filename.endswith('.txt'):
        # Copy the file

shutil.copy(filename, '/path/to/destination')
```


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!