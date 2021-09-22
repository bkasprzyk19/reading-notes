[<==Back](README.md)

What does REST stand for?

Representational State Transfer, proposed by Roy Fielding, as an architectural approach to designing web services.

REST APIs are designed around a ____.

resource, which are any kind of object. data. or service that can be accessed by the client.

What is an identifer of a resource? Give an example.

a URI that uniquely identifies that resource, for example: https://adventure-works.com/orders/1

What are the most common HTTP verbs?

GET, POST, PUT, PATCH, DELETE

What should the URIs be based on?

nouns (the resource) and not the verbs (operations of resource)

Give an example of a good URI.

https://adventure-works.com/orders // Good



What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

They are exposing a large number of small resources instead of sending a larger chunk of data at the same time. It is bad to do this and better to get more data in one get.

What status code does a successful GET request return? 200
What status code does an unsuccessful GET request return? 404
What status code does a successful POST request return? 201
What status code does a successful DELETE request return? 204