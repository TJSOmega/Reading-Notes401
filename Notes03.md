# Read 03

#### Routing:
 You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. For a full list, see app.METHOD. You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function (See Using middleware for details).


 **There is a special routing method, app.all()**, used to load middleware functions at a path for all HTTP request methods. For example, the following handler is executed for requests to the route “/secret” whether using GET, POST, PUT, DELETE, or any other HTTP request method supported in the http module.

*app.all('/secret', function (req, res, next) {
  console.log('Accessing the secret section ...')
  next() // pass control to the next handler
})*


Route parameters
Route parameters are named URL segments that are used to capture the values specified at their position in the URL. The captured values are populated in the req.params object, with the name of the route parameter specified in the path as their respective keys.

Route path: /users/:userId/books/:bookId
Request URL: http://localhost:3000/users/34/books/8989
req.params: { "userId": "34", "bookId": "8989" }
To define routes with route parameters, simply specify the route parameters in the path of the route as shown below.

app.get('/users/:userId/books/:bookId', function (req, res) {
  res.send(req.params)
})
The name of route parameters must be made up of “word characters” ([A-Za-z0-9_]).


1. ##### Name 3 real world use cases where you’d want to change the request with custom middleware
1. Will have to return with the answer for this one.

2. ##### True or false: The route handler is middleware?
2. False, the route handler is in a category all on its own.

3. ##### In what ways can a middleware function end the process and send data to the browser?
3. By using the Next() method

4. ##### At what point in the request lifecycle can you “inject” middleware?
4. Prior to the request call, the middleware gets picked up and added to the route

5. ##### What can cause express to error with “Request headers sent twice, cannot start a second response”
5 Will have to return with the answer for this one.