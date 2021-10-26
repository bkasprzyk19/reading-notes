[<==Back](README.md)

## Explain what a “Singleton” is (in Computer Science terms)

https://betterprogramming.pub/what-is-a-singleton-2dc38ca08e92

- restricts the instantiation of a class to a single instance. 
- provides coordinated access to a single resource
- considered an alternative to global variables

## Explain how the Singleton pattern can be used with Node modules, specifically with classes



## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

http://expressjs.com/en/guide/using-middleware.html

### Middleware functions can perform the following tasks:

- Execute any code.
- Make changes to the request and - the response objects.
- End the request-response cycle.
- Call the next middleware function in the stack.


## Router Middleware

http://expressjs.com/en/guide/using-middleware.html#middleware.router

Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router().
``` js
var router = express.Router()
```
## Dynamic Module Loading

https://dev.to/hasnaindev/dynamic-module-pattern-for-javascript-dynamically-load-javascript-bundles-m5c

- you define in markup what JS should be loaded


## Singleton Pattern

- A creational design pattern that restricts the instantiation of a class to one object.


## CRUD -> REST Method Matches


Create = PUT with a new URI
         POST to a base URI returning a newly created URI
Read   = GET
Update = PUT with an existing URI
Delete = DELETE

## Mock Testing

- building test files to automatically run or use thunderclients