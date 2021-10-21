[<==Back](README.md)


## Name 3 real world use cases where you’d want to change the request with custom middleware
 - to alter data before it gets to the route
 - edit requests
 - logging
 - validating
 - order array

 https://expressjs.com/en/guide/writing-middleware.html

## True or false: The route handler is middleware?

- it can be consifered a middleware function and a handler function if it has the req, res, next. they are not opposite of eachother

https://stackoverflow.com/questions/58925276/what-is-the-difference-between-a-route-handler-and-middleware-function-in-expres#:~:text=They%20are%20not%20middleware%20functions,the%20only%20one%20callback%20function.


## In what ways can a middleware function end the process and send data to the browser?

- put a string in the next('string here') which trips the error
 source -myself

## At what point in the request lifecycle can you “inject” middleware?

- i think in the middle between the http method and the route its headed


## What can cause express to error with “Request headers sent twice, cannot start a second response”

- another function already sent or was used twice

Middleware
- software that acts as a bridge between an operating system or database and applications, esp on a network

Request Object
-https://book.cakephp.org/3/en/controllers/request-response.html

Response Object
-https://book.cakephp.org/3/en/controllers/request-response.html

Application Middleware
- bound to an instance?
- app.use()

Routing Middleware
- express.Router()


Test Driven Development
- software process relying on software requirements being converted to test cases before the software is fully dev'd

Behavioral Testing ?