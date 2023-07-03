# 401 class 16 notes

**Why this matters**: This information matters because being able to pull and use data from APIs increases what you're able to do with Python applications.

------------------------------------

**1. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?**

Serverless Computing refers to implementing a system or application that does not rely on centralized, dedicated servers. It exhibits the following characteristics:

- On-Demand execution
- Elastic
- No host
- Distributed
- Shorter execution time

It differs from traditional server-based architecture in that it doesn't need centralized, dedicated servers, as it moves responsibility for operations and management of servers to a cloud provider.

[Source](https://dev.to/bpb_online/characteristics-of-serverless-computing-2ij4)
[Source](https://www.ingeno.ca/blog/the-characteristics-of-serverless-architecture)


**2. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?**

To get started with Vercel, readers need to understand projects (apps deployed to Vercel) and deployments (result of a successful build of a project).

The steps include (1) either deploying a template or importing and deploying an existing project, (2) assigning a custom domain to their project, and (3) collaborating and making changes to the project.

[Source](https://vercel.com/docs/getting-started-with-vercel/projects-deployments)

**3. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?**

Application Programming Interfaces (APIs) act as a communication layer -  or interface -  that allows different systems to talk to one another without having to understand exactly what the other one does.

Pperating system APIs are used for actions like turning on your camera and audio for joining a Zoom call. Web APIs are used for web-focused actions such as liking images on your Instagram or fetching the latest tweets.

They function by (1) user making a request for information or data, and (2) API returns a response with what was requested. For example, every time you open Twitter or scroll down your Instagram feed, you’re basically making a request to the API behind that app and getting a response in return. This is also known as calling an API.

[Source](https://realpython.com/python-api/)

**4. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?**

The `requests` library in Python allows users to perform actions required to consume public APIs. It's installed using the command:

```$ python -m pip install requests```

The requests library can interact with APIs by fetching data from the API URL with the `requests.get(URL)` command. 

In the article's example API called the Random User Generator API, they get data from the API using the following line of code;

`requests.get("https://randomuser.me/api/")`

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!