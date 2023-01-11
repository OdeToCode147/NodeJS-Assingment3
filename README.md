<h1>What is Middleware in NodeJS</h1>
A request handler with access to the application's request-response cycle is known as middleware. It's a function that holds the request object, the response object, and the middleware function. Middleware can also send the response to the server before the request.
<br>
<hr>
<h1>Why is middleware used in Express?</h1>
An Express-based application is a series of middleware function calls. Advantages of using middleware: Middleware can process request objects multiple times before the server works for that request. Middleware can be used to add logging and authentication functionality.
<br>
<hr>
<h1>What is next() function</h1>
Next function is a very important, after the end of each middleware we should execute next function so that the program execution can move either to next middleware or the main route,if this function is not added then execution will not move forward.
