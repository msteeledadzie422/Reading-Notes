# ES6 Classes

1. Classes are a template for creating ____.

    Classes are a template for creating objects.

2. Can a class declaration be hoisted?

    Yes, but classes must be defined before they can be constructed - this is a key difference between function declarations and class declarations.

3. How would you describe a constructor and contextual “this” to a non-technical friend?

    Within a constructor, when a static prototype method is called without a value for this, such as by assigning the method to a variable and the ncalling it, the this value will be undefined inside the method. 
    

# Using Express Routing

1. Within Express, what does routing refer to?

    Routing refers to how an application's endpoints (URIs) respond to client requests.

2. What is the difference between a route path and a route method?

    Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string paterns, or       regular expressions.
    
    A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

    When using multiple callback functions, it is important to provide a next argument to the callback function and to call next() within the body of the       function to hand off control to the next callback.


# Express Routing

1. What is an Express Router?

    An Express router is like a mini-Express application. It does not bring in views or settings but provides us with the routing APIs like .use, .get,         .param, and route.
    
2. By what mean do we initialize express.Router() in an express server?

    We create a variable called router that is express.Router() and then we use app.use to apply the routes to our application.

3. What do we use route middleware for?

    Route middle in Express is away to do something before a request is processed. This could be things like checking if a user is authenticated, logging       data for analytics, or anything else we'd like to do before we actually spit out information to our user.
