# 401 class 29 notes

**Why this matters**: This information matters because the Custom User Model is important in customizing authentication processes and DjangoX provides helpful templates and packages for Django projects.

------------------------------------

**1. What are the key benefits of using a Django Custom User Model, and how does it differ from the default Django User Model?**

Some of the key benefits are greater flexibility, customization, security, scalability, and integration with third party apps.

It differs in several ways, including:

- Fields and schema: the default comes with pre-defined fields like "username", "email", and "password". Custom allows you to create your own fields and schema.
- Flexibility and customization options: are greater with the Custom User Model
- Authentication: the default handles authentication using a username and password, but the Custom User Model allows you to define the authentication method.
- Unique identifiers: the default users "username", but customizing allows you to use email or another identifier.

[Source](https://learndjango.com/tutorials/django-custom-user-model)

[Source](https://testdriven.io/blog/django-custom-user-model/#:~:text=It's%20highly%20recommended%20to%20set,fields%20to%20the%20user%20model.)

**2. Explain the process of creating and implementing a Custom User Model in Django, including the necessary changes to settings.py and the required model fields.**

1. Create a new Django app using `python manage.py startapp name_of_app`

2. Define the Custom User Model by going into models.py and subclassing `AbstractBaseUser` and `PermissionsMixin` from Django's `django.contrib.auth.models`. These classes provide the necessary methods and fields for user authentication and permissions.

3. Add the Custom User Model to the settings.py file. Specify the `AUTH_USER_MODEL` to tell Django to use your Custom User Model instead of the default User model. Use the app name and the model name in the format "app_name.ModelName".

4. Create and apply database migrations to create the new user model's table in the database via `python manage.py makemigrations`
and `python manage.py migrate`

5. Update existing references to the User model to use the new Custom User Model. Replace `from django.contrib.auth.models import User` with `from myapp.models import CustomUser`

[Source](https://www.youtube.com/watch?v=eCeRC7E8Z7Y&t=59s)

**3. What is DjangoX and how does it complement or extend the functionality of Django? Provide an example use case for incorporating DjangoX in a project.**

DjangoX is a project template and a set of additional packages that complement and extend the functionality of Django.

It extends Django functionality in the following ways:

- project template with organized directory structure and settings
- pre-installed and pre-configured packages common to Django projects
- pre-configured database settings
- ready-to-use user authentication system
- static file directories (and configs like CSS, JS, images) available through project template
- Django Extensions package with management commands and utilities
- deployment-related configs for various platforms

[Source](https://github.com/wsvincent/djangox)
[Source](https://wsvincent.com/djangox-new-starter-framework/)
------------------------------------
### Things I Want To Know More About:
Nothing at the moment!