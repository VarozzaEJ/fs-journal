# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create, Read, Update, Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > POST, GET, PUT, DELETE

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object Relational Mapping. We use mongoose

04. Which two `HTTP` request types include a body?

  > PUT and POST are the two that have bodies attached to them.

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > asynchronous, synchronous

06. What are the three types of data relationships? Provide an example of each.

  > One To One: One piece of data relates to only one piece of different data, One To Many: One piece of data relates to multiple different pieces of data, Many To Many: Many pieces of data relate to many other different pieces of data. 

07. What is middleware?

  > Middleware is the bridge that connects to different things together. This could be software to software or a user to software.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > Request, Response

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > xxx/?tag=winter

10. What is a ***virtual property***?

  > A virtual property is a property that is added to a piece of data using something similar to getters in a model. It must be populated after being declared and it must be populated in the controler. They connect one database to another using reference names.
