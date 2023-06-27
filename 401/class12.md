# 401 class 12 notes

**Why this matters**: This information matters because it details the Pandas Library and how it can be used in a Python project to help with data sets.

------------------------------------

**1. Explain the purpose and basic functionality of the Pandas library. What are some common operations that can be performed on data using Pandas, and how do they contribute to data analysis and manipulation?**

Pandas is a Python library used for working with data sets. It has functions for analyzing, cleaning, exploring, and manipulating data.

Pandas gives you answers about the data such as

- Is there a correlation between two or more columns?
- What is average value?
- Max value?
- Min value?
- Pandas are also able to delete rows that are not relevant, or contains wrong values, like empty or NULL values. This is called cleaning the data.

[Source](https://www.w3schools.com/python/pandas/pandas_intro.asp#:~:text=Pandas%20is%20a%20Python%20library,by%20Wes%20McKinney%20in%202008.)

**2. What are the primary data structures in Pandas, and how do they differ in terms of use cases?**

Series: a one-dimensional array holding data of any type. Like a column or table.

DataFrame: a two-dimensional data structure, like a two-dimensional array or a table with rows and columns.

They differ by use cases in that if you are only dealing with one dimension, like a column, you can utilize Series. If you are working with two dimensions, like a table with rows and columns, you can utilize DataFrame.

[Source](https://www.w3schools.com/python/pandas/pandas_dataframes.asp)

**3. Describe the process of loading a dataset into a Pandas DataFrame. What are some common file formats that can be used, and which Pandas functions are utilized to read these formats?**

1. Load the packages, pandas as pd and datetime as dt

2. Use the associated function depending on file type:

- CSV files (the most common) and remote CSV files , use `read_csv()`
- TSV files, also `read_csv()`
- Excel files, `read_excel()`
- HTML files, `read_html()`
- Yaml files, `yaml.load()`

There's many more functions you can use for other file types.

[Source](https://practicaldatascience.co.uk/data-science/how-to-import-data-into-pandas-dataframes#:~:text=To%20import%20a%20CSV%20file,file%20you%20wish%20to%20read.)
------------------------------------
### Things I Want To Know More About:
Nothing at the moment!