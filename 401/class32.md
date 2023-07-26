# 401 class 32 notes

**Why this matters**: This information matters because DRF and SQL are both important to us understanding where to take our Django projects and APIs next.

------------------------------------


**1. What are the key components and purpose of Django Rest Framework (DRF) permissions, and how do they help in securing an API?**

The purpose of permissions is that they determine whether a request should be granted or denied access.

Components include: authentication, permission classes, object level permissions, permission checks, global view/viewset level configuration, and custom permissions.

[Source](https://www.django-rest-framework.org/api-guide/permissions/)

**2. In SQL, what is the purpose of the SELECT statement, and how would you use it to retrieve all columns from a table called ‘employees’?**

The SELECT statement retrieves data from a database - it specifies the columns and rows that should be retrieved from table(s). 

You could retrieve all columns from a table called 'employees' by using the following line:
`SELECT * FROM employees`

[Source](https://codefellows.github.io/common_curriculum/prework/SQL)

**3. Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?**

DRF Generic Views allow you to quickly build API views that map closely to your database models - it's a shortcut for common usage patterns.

According to the reading, in this example, the view is overridden and class attributes are set in the following Generic View:

```python
from django.contrib.auth.models import User
from myapp.serializers import UserSerializer
from rest_framework import generics
from rest_framework.permissions import IsAdminUser

class UserList(generics.ListCreateAPIView):
    queryset = User.objects.all()
    serializer_class = UserSerializer
    permission_classes = [IsAdminUser]
```

In the following example, variouys methods on the view class are overridden:

```python
class UserList(generics.ListCreateAPIView):
    queryset = User.objects.all()
    serializer_class = UserSerializer
    permission_classes = [IsAdminUser]

    def list(self, request):
        # Note the use of `get_queryset()` instead of `self.queryset`
        queryset = self.get_queryset()
        serializer = UserSerializer(queryset, many=True)
        return Response(serializer.data)
```

[Source](https://www.django-rest-framework.org/api-guide/generic-views/)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!