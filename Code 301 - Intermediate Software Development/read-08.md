# Reading Notes: APIs

> What does REST stand for?

- REST stands for Representational State Transfer.

> REST APIs are designed around a ____?

- REST APIs are designed around a stateless client-server architecture.

> What is an identifier of a resource? Give an example.

- An identifier of a resource is a unique name or address used to find that particular resource. For instance, a URL like "https://www.example.com/page1.html" is an identifier for a web resource.

> What are the most common HTTP verbs?

- GET: Retrieve a resource.
- POST: Create a new resource.
- PUT: Update an existing resource.
- DELETE: Delete a resource.

> What should the URIs be based on?

- URIs should be based on consistent and meaningful ways to identify resources, following established standards for accessibility and persistence.

> Give an example of a good URI.

- URI is a web address (URL) like "https://www.example.com/page1.html".

> What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- A 'chatty' web API means it requires many small requests to get a task done. It's generally considered bad as it can slow down performance due to increased network traffic.

> What status code does a successful GET request return?

A successful GET request returns a status code of 200 OK.

> What status code does an unsuccessful GET request return?

- An unsuccessful GET request typically returns a status code of 404 Not Found or 400 Bad Request.

> What status code does a successful POST request return?

- A successful POST request returns a status code of 201 Created or 200 OK.

> What status code does a successful DELETE request return?

- A successful DELETE request returns a status code of 204 No Content.