# 401 class 33 notes

**Why this matters**: This information matters because JWT is an important tool for upgrading authentication and app security, and we need alternate options to the Django built-in runserver for larger and more complex projects.

------------------------------------

**1. What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?**

JSON Web Tokens define a compact and self-contained way for securely transmitting information between parties as a JSON object.

JWTs consist of three parts separated by dots: the header, the payload, and the signature. The header includes the token type (JWT) and the signing algorithm used to create the signature. This JSON object is then Base64Url encoded to form the first part of the JWT.

The payload has claims - statements about an entity, plus additional data.  Public claims are custom claims that can be defined by the creator of the JWT. Private claims are used to share information between parties that agree on their usage and are neither registered nor public claims.

[Source](https://jwt.io/introduction/)
[Source](https://jwt.io/introduction#:~:text=What%20is%20JSON%20Web%20Token,because%20it%20is%20digitally%20signed.)

**2. How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?** 

- Install `djangorestframework` and `djangorestframework-simplejwt`
- Configure Django Settings
- Create authentication views to be used in urls.py
- Secure API endpoints

[Source](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)

**3. Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?**

Because of security concerns, performance limitations, stability and reliability, static files handling, and scalability.

You can consider Gunicorn, uWSGI, Daphne, ASGI Servers like uvicorn and Hypercorn, or FastCGI.

[Source](https://vsupalov.com/django-runserver-in-production/) and chatGPT help

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!