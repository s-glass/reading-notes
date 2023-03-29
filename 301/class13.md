# 301 class 13 notes

**Why this matters**: This information matters because it defines the functions and methods used in CRUD, and gives us a very fast demo of creating a CRUD API via Twitch.

------------------------------------

## CRUD Basics

Source: [https://medium.com/geekculture/crud-operations-explained-2a44096e9c88](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)

**1. Which HTTP method would you use to update a record through an API?**

PUT, it replaces all current data of the target resource with the uploaded content.

**2. Which REST methods require an ID parameter?**

PUT and DELETE

----------------------------

## Speed Coding: Building a CRUD API

Source: [https://www.youtube.com/watch?v=EzNcBhSv1Wo](https://www.youtube.com/watch?v=EzNcBhSv1Wo)

**1. What’s the relationship between REST and CRUD?**

REST is an architectural system centered around resources and Hypermedia using HTTP commands. CRUD is a cycle meant to maintain records in a database setting. CRUD is a way of manipulating information, describing the function of an application. [Source](https://www.logicmonitor.com/blog/rest-vs-crud#:~:text=REST%20is%20an%20architectural%20system,controlling%20data%20through%20HTTP%20commands.)

**2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**

1. Identify resources - Object Modeling

2. Create Model URIs (resource URIs = API endpoints)

3. Determine resource representations (defined in either XML or JSON)

4. Assigning HTTP methods (map app operations to resource URIs)

5. More Actions: logging, security, discovery, etc.

[Source](https://restfulapi.net/rest-api-design-tutorial-with-example/)

------------------------------------
### Things I Want To Know More About:
- Generating a server with the `npx create-express-api` command!
- What's the difference between URI and URL? [Source](https://www.hostinger.com/tutorials/uri-vs-url#:~:text=URI%20identifies%20a%20resource%20and,a%20domain%20name%20and%20port.)
- What's the difference between Node.js and React? Node.js is a JS framework geared towards backend dev and React is a library geared towards frontend dev.
