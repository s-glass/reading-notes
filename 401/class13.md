# 401 class 13 notes

**Why this matters**: This information matters because it details Linear Regression in Python, which we will need to understand in order to work with data and machine learning / AI.

------------------------------------

**1. Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?**

Linear regression calculates the `estimators` of `regression coefficients` or `predicted weights`. These estimators define the `estimated regression function`, which is what expresses the dependencies between the inputs and outputs from a given dataset. Ultimately, linear regression helps to calculate the dependencies/relationship between two variables; it's a component of predictive data analysis.

[Source](https://realpython.com/linear-regression-in-python/)

**2. Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions.**

Step 1: Import the packages and classes needed in this example:
import numpy as np.

Step 2: Create a numpy array of data.

Step 3: Create an instance of a linear regression model and fit it to the data with the `fit()` function.

Step 4: Obtain the coefficient of determination by calling the model with the `score()` function, then print the coefficient

Step 5: Print the Intercept.

Step 6: Print the Slope.

Step 7: Predict a response and print it.

[Source](https://www.activestate.com/resources/quick-reads/how-to-run-linear-regressions-in-python-scikit-learn/)


**3. What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?**

To avoid biased evaluation, you can’t evaluate the predictive performance of a model with the same data you used for training. You need evaluate the model with fresh data that hasn’t been seen by the model before, accomplished by splitting your dataset before you use it.

[Source](https://realpython.com/train-test-split-python-data/)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!