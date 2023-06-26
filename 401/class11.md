# 401 class 10 notes

**Why this matters**: This information matters because 
------------------------------------

**1. What are the key features and benefits of Jupyter Lab, and how does it differ from Jupyter Notebook?**

JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.

- You can arrange multiple documents and activities side by side in the work area using tabs and splitters.

- Documents and activities integrate with each other, enabling new workflows for interactive computing, for example:

- Code Consoles provide transient scratchpads for running code interactively, with full support for rich output. A code console can be linked to a notebook kernel as a computation log from the notebook, for example.

- Kernel-backed documents enable code in any text file (Markdown, Python, R, LaTeX, etc.) to be run interactively in any Jupyter kernel.

- Notebook cell outputs can be mirrored into their own tab, side by side with the notebook, enabling simple dashboards with interactive controls backed by a kernel.

- Multiple views of documents with different editors or viewers enable live editing of documents reflected in other viewers. For example, it is easy to have live preview of Markdown, Delimiter-separated Values, or Vega/Vega-Lite documents.

- JupyterLab also offers a unified model for viewing and handling data formats. JupyterLab understands many file formats (images, CSV, JSON, Markdown, PDF, Vega, Vega-Lite, etc.) and can also display rich kernel output in these formats. See File and Output Formats for more information.

- To navigate the user interface, JupyterLab offers customizable keyboard shortcuts.

- JupyterLab extensions can customize or enhance any part of JupyterLab, including new themes, file editors, and custom components.

Jupyter notebook is different from Jupyter Lab in that Jupyter notebook only offers a very simple interface using which users can open notebooks, terminals, and text files. Jupyter lab offers a very interactive interface that includes notebooks, consoles, terminals, CSV editors, markdown editors, interactive maps, and more.

[source](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html)
[source](https://www.dominodatalab.com/data-science-dictionary/jupyter-notebook#:~:text=Jupyter%20notebook%20only%20offers%20a,%2C%20interactive%20maps%2C%20and%20more.)


**2. What are the main functionalities provided by the NumPy library, and how can it be useful in Python programming, particularly for scientific computing and data manipulation tasks?**

NumPy is a Python library used for working with arrays, with functions for working in domain of linear algebra, fourier transform, and matrices.

It can be useful for scientific computing and data manipulation tasks using Python because NumPy can provide an array object that is up to 50x faster than traditional Python lists. And since arrays are frequently used in data science, speed and resources are very important.

[source](https://www.w3schools.com/python/numpy/numpy_intro.asp#:~:text=NumPy%20is%20a%20Python%20library,you%20can%20use%20it%20freely.)

**3. Explain the basic structure and properties of NumPy arrays, and provide examples of how to create, manipulate, and perform operations on them.**

NumPy is used to work with arrays. The array object in NumPy is called `ndarray`.

We can create a NumPy `ndarray` object by using the `array()` function.

For example:
```
import numpy as np

arr = np.array([1, 2, 3, 4, 5])

print(arr)

print(type(arr))
```



------------------------------------
### Things I Want To Know More About:
Nothing at the moment!