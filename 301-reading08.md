# API Design Best Practices

1. REST stands for Representational State Transfer - an architectural approach to designing web services proposed by Roy Fielding in 2000.
2. REST APIs are designed around resources, which are any kind of object, data, or service that can be acccessed by the client.
3. An identifier of a resource is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: https://adventure-works.com/orders/1.
4. The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.
5. When possible, URIs should be based on nouns and not verbs.
6. https://adventure-works.com/orders // Good
7. A "chatty" API is one that exposes a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. You want to avoid chatty APIs.
8. A successful GET request typically returns HTTP status code 200 (OK).
9. An unsuccessful GET request typically returns HTTP status code 204 (No Content).
10. A successful POST request returns HTTP status code 201 (Created).
11. A successful DELETE request returns HTTP status code 204 (No Content).
