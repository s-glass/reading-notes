# 401 class 34 notes

**Why this matters**: This information matters because it gives us info on detailing settings.py, including adding CORS to help manage security via allowed domains, and the White Noise library to manage static files easily.

------------------------------------

**1. What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?**

- Keep settings in environment variables
- Write default values for production configuration (excluding secret keys and tokens)
- Don't hardcode sensitive settings and don't put them in VCS
- Split settings into groups like Django, third-party, project, etc.
- Follow naming conventions for custom project settings


[Source](https://djangostars.com/blog/configuring-django-settings-best-practices/)

**2. How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?**

It allows your app to serve it's own static files by adding a few lines of config, making it able to be deployed anywhere without relying on external services. It also has special auto-config features for Django like compressed content and far-future cache headers.

Install with `pip install whitenoise`, and add WhiteNoise to the middleware list in settings.py above all other middleware except for Django security middleware.

[Source](https://whitenoise.readthedocs.io/en/stable/)

**3. What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?**

CORS allows restricted resources on a web page to be accessed from a separate domain from where the first resource came from. It prevents unauthorized access to resources hosted on a different domain.

CORS can be added to a Django project through the `django-cors-headers` package. To do this: (1) install `django-cors-headers` via pip, (2) add `corsheaders` to settings.py django installed apps, (3) in settings.py, specify the list of allowed domains under CORS_ALLOWED_ORIGINS, (4) and finally, also in settings.py include `CorsMiddleware` in middleware.


[Source](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing) and chatGPT help to clarify.

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!