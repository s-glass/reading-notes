# 401 class 14 notes

**Why this matters**: This information matters because it covers key tools and concepts in data visualization.

------------------------------------

**1. What are the key differences between Matplotlib, Seaborn, and Bokeh libraries in terms of their features and use cases? Provide an example of a specific visualization that is more suitable for each library.**

matplotlib is for basic plotting -- bars, pies, lines, scatter plots, etc.

Seaborn is for statistical visualization -- use it if you're creating heatmaps or somehow summarizing your data and still want to show the distribution of your data

Bokeh is for interactive visualization -- if your data is so complex (or you haven't yet found the "message" in your data), then use Bokeh to create interactive visualizations that will allow your viewers to explore the data themselves

[Source](https://www.reddit.com/r/Python/comments/4tuwoz/how_do_you_decide_between_the_plotting_libraries/)

**2. In the Seaborn library, what are the main functions to create relational, categorical, and distribution plots? Briefly explain the purpose of each type of plot and provide an example use case.**

**Relational Plots:**

`sns.scatterplot():` Creates a scatter plot to show the relationship between two variables.
`sns.lineplot():` Generates a line plot to display the relationship between two variables.
`sns.relplot():` Provides a high-level interface to create various relational plots, including scatter plots, line plots, and more.

**Categorical Plots:**

`sns.barplot()`: Constructs a bar plot to represent the relationship between a categorical variable and a numeric variable.
`sns.countplot()`: Displays the count of occurrences for each category in a categorical variable.
`sns.boxplot()`: Generates a box-and-whisker plot to show the distribution of a numeric variable across different categories.
`sns.violinplot()`: Creates a violin plot that combines a box plot and a kernel density estimation.
`sns.swarmplot()`: Produces a categorical scatter plot by placing individual data points on a categorical axis.

**Distribution Plots:**

`sns.histplot()`: Constructs a histogram to visualize the distribution of a single variable.
`sns.kdeplot()`: Generates a kernel density plot to estimate the distribution of a single variable.
`sns.distplot()`: Deprecated since Seaborn version 11.0. Use `sns.histplot()` or `sns.kdeplot()` instead.
`sns.rugplot()`: Adds small vertical lines (rug plot) to represent the distribution of a single variable.

[Source](https://seaborn.pydata.org/)

**3. Discuss the role of the Seaborn Cheat Sheet in a Python developer’s workflow. What are some key sections or elements featured in the cheat sheet that can help a developer quickly reference Seaborn functionalities?**


The Seaborn Cheat Sheet is a reference tool for people who want to work with the Seaborn data visualization library. It shows 'at-a-glance' info and functions for working with Seaborn.


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!