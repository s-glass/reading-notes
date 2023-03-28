# 301 class 12 notes

**Why this matters**: This information matters because it details various status codes and when to use them, along with demonstrating a fast but efficient run through of creating a REST API.

------------------------------------

## Status Codes Based On REST Methods

Source: [https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

**1. In your own words, describe what each group of status code represents:**

100’s = informational codes; typically they tell the client that the header of the request has been received and that the server will try to comply with a transmission demand of the client.

200’s = success codes; they tell the client that the request was accepted.

300’s = redirection codes; they tell the client that the resource being requested isn't available at the expected location.

400’s = client error codes; they alert the client to invalid requests to a server.

500’s = server error codes; typically they mean there's problems with overwhelmed servers or unreachable servers behind proxies. Sometimes they can be directly related to client requests that trigger error exceptions on the server.


**2. What is a status code 202?**

Accepted. Tells the client that the request was valid, but processing will finish sometime in the future.

**3. What is a status code 308?**

Permanent redirect. Resource will now be available at a new URL and client should directly access it via the new URL in the future.

**4. What code would you use if an update didn’t return data to a client?**

204 No content.

**5. What code would you use if a resource used to exist but no longer does?**

204 No content.

**6. What is the ‘Forbidden’ status code?**

403, client has authorized or doesn't need to authorize itself, but still has no permissions to access the resource.

----------------------------

## Build a REST API With Node.js, Express & MongoDB - Quick 

Source: [https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

**1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

Because we will want to use something that isn't the local host, so we add it to the .env.

**2. What is middleware?**

Code that runs when the server gets a request, but before it gets passed to your routes.

**3. What does app.use(express.json()) do?**

`app.use` allows us to use whatever middleware we want. `express.json` allows the server to accept JSON as a body instead of a post element or get element, etc.

**4. What does the /:id mean in a route?**

the `:` means it's a parameter that can be 
 accessed with `req.params.id` to give access to whatever they pass in after the first slash. 

**5. What is the difference between PUT and PATCH?**

Patch updates based only on what the user passes you. Put updates all information at once instead of just the information that gets passed.

**6. How do you make a default value in a schema?**

`default: Date.now` so that in the examppe, if we don't pass our subscribed date it will default to the current date.

**7. What does a 500 error status code mean?**

It means that there's an error on your server. the server (db) had an error that caused the transaction not to work and doesn't have to do with the user - it's entirely the dev's faut.

**8. What is the difference between a status 200 and a status 201?**

201 means successfully created an object; 200 means everything was successful. 201 is more specific.

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!