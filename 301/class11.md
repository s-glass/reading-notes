# 301 class 11 notes

**Why this matters**: This information matters because it introduces us to ways that databases can be accessed, assessed, and manipulated with SQL and NoSQL frameworks.

------------------------------------

## NoSQL vs SQL

Source: [https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

**5 differences between NoSQL and SQL**
| NoSQL  |  SQL   |
| ------ | ------ |
| non-relational or distributed database  |  RDBMS: relational database  |
| document, key-value pair, graph, or wide-column stores-based  | table-based |
| dynamic schema for unstructured data | predefined schema for unstructured data |
| horizontally scalable | vertically scalable  |
| not good for complex queries | good for complex queries |

**1. What kind of data is a good fit for an SQL database?**

Complex queries; table-based data; non-heirarchical data.

**2. Give a real world example.**

MySQL database, a popular open-source database that can be stacked with apache, PHP, nginx, and server side javascripting using Node js.

**3. What kind of data is a good fit a NoSQL database?**

Heirarchical data storage; key-value pairs, graphs, wide-column stores, documents; large data sets.

**4. Give a real world example.**

MongoDB, one of the most popular non-relational, document-based NoSQL databases with dynamic schema. Stores data in JSON like documents. It's written in C++.

**5. Which type of database is best for hierarchical data storage?**

NoSQL.

**6. Which type of database is best for scalability?**

SQL for vertical scalability (increasing CPU, RAM, SSD, etc. on one server), NoSql for horizontal scalability (increasing number of servers).

----------------------------

## What Is Props And How To Use In React

Source: [https://www.youtube.com/watch?v=ZS_kXvOeQ5Y](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

**1. What does SQL stand for?**

Structured Query Language


**2 What is a relational database?**

It works with assumptions and supports the SQ language; these databases work with tables.

**3. What type of structure does a relational database work with?**

Tables.

**4. What is a ‘schema’?**

Strict requirements for the data stored in the database tables: which data can and can't go into a table. This is defined by fields (ex. id, name, price, description).

**5. What is a NoSQL database?**

MongoDB, large data stored efficiently. In general, they have no relations.

**6. How does it work?**

Databases with collections instead of tables. Collections have documents (like rows in a table, but they look like JSON and don't have to use the same schema); you can have multiple structures of data (one row has XYZ, another has ABZ).

**7. What is inside of a MongoDB database?**

Collections with documents.

**8. Which is more flexible - SQL or MongoDB? and why.**

MongoDB because it's not beholden to data schema/formats.

**9. What is the disadvantage of a NoSQL database?**

SQL has normalized, distributed data that can be merged together with SQL queries.

------------------------------------
### Things I Want To Know More About:
The difference between:
- A backend = parts of an app not accessed by a user.
- A server = network servers manage traffic, file servers store and retrieve files for clients.
- An API = interface that allows 2+ programs to communicate with each other.
- A database = structured set of data.