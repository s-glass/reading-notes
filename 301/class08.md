# 301 class 08 notes

**Why this matters**: This information matters because it outlines the design best practices for APIs.

------------------------------------

## API Design Best Practices

Source: [https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

**1. What does REST stand for?**

Representational State Transfer (REST)

**2. REST APIs are designed around a ____.**

resource - any kind of object, data, or service that can be accessed by the client.

**3. What is an identifier of a resource? Give an example.**

A URI that uniquely identifies that resource. For example, the URI for a specific customer's order could be: 

`https://adventure-works.com/orders/1`

**4. What are the most common HTTP verbs?** 

GET, POST, PUT, PATCH, DELETE

**5. What should the URIs be based on?**

Nouns (the resource) and not verbs (the operations on the resource).

**6. Give an example of a good URI.**

`https://adventure-works.com/orders`

**7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

It means that the API exposes a large number of small resources. This can be negative, as it requires a client application to send multiple requests to find all of the data that it requires, and can impose a larger load on the web server.

**8. What status code does a successful GET request return?**

200 (ok)

**9. What status code does an unsuccessful GET request return?**

404 (not found)

**10. What status code does a successful POST request return?**

If it creates a new resource: 201 (created)
If it processes but doesn't create a new resource: 200 (ok)

**11.What status code does a successful DELETE request return?**

204 (No Content)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!