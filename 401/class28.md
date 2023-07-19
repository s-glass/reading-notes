# 401 class 28 notes

**Why this matters**: This information matters because Forms, Templates, and Views are all key components in building out webpages with Django.

------------------------------------

**1. How do Django Forms facilitate user input handling, and what are some key components of creating a form using the Django framework?**

Django Forms facilitate the handling of user input by providing a high-level, Pythonic way of processing form data on the server side. They allow you to define the structure of a form and validate the submitted data. By using Django Forms, you can easily generate HTML for the form, handle user input, perform validation, and store the validated data in your database or process it as required.

Some key components of creating a form include:

- importing necessary modules
- defining form class
- form fields
- form validation
- rendering form in template
- handling form submission
- displaying form errors

[Source](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms) plus chatGPT help



**2. Explain the purpose of Django Templates in web development and describe how template inheritance can be utilized to improve code reusability and maintainability.**

The purpose of Django Templates is to provide a way to create dynamic HTML pages by combining HTML markup with template tags and filters, allowing developers to inject dynamic content into the final HTML output.

Template inheritance allows for a base template that contains common structure and elements shared across multiple pages along with defining sections that can be overridden or extended in child templates.

This conecpt improves code reusability and maintainability in these ways:

- Reduced duplication: Changes to the base template automatically apply to all child templates, making updates more efficient.

- Consistency: Common elements remain the same in all child templates.

- Modularity: Devs can focus on specific sections of the website without worrying about the overall layout and structure.

- Easy maintenance: When changes are needed only the base template or the specific blocks in the child templates need to be changed.

[Source](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page) plus chatGPT help



**3. Describe the function of Django Views in handling HTTP requests, and outline the differences between function-based views and class-based views.**

Views play a crucial role in handling HTTP requests and returning HTTP responses. As Python functions or classes, they're responsible for processing user requests, interacting with the database or other data sources, and rendering the appropriate response, typically in the form of an HTML page or JSON data.

Function-based views are the traditional way of defining views in Django. They are Python functions that take an HTTP request as input and return an HTTP response. They are defined as Python functions, easy to use, and use a procedural approach.

Class-based views are an alternative way of defining views in Django. They use Python classes to handle HTTP requests and responses, and provide a more object-oriented approach to organizing views. They are defined as Python classes, are reusable and modular, come with built-in generic class-based views, and can be combined with Python mixins for further functionality.

[Source](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views) plus chatGPT help



------------------------------------
### Things I Want To Know More About:
Nothing at the moment!