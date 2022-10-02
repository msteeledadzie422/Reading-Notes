# ES6 Classes

1. Classes are a template for creating ____.

    Classes are a template for creating objects.

2. Can a class declaration be hoisted?

    Yes, but classes must be defined before they can be constructed - this is a key difference between function declarations and class declarations.

3. How would you describe a constructor and contextual “this” to a non-technical friend?

    Within a constructor, when a static prototype method is called without a value for this, such as by assigning the method to a variable and the ncalling it, the this value will be undefined inside the method. 
    

# Using Express Routing

1. Within Express, what does routing refer to?



2. What is the difference between a route path and a route method?



3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?


# Express Routing

1. What is an Express Router?

    Express Routers are how an application's endpoints (URIs) respond to client requests. You define routing using methods od the Express app object that correspond to HTTP methods. For example, app.get() to handle GET requests and app.post() to handle POST requests.

2. By what mean do we initialize express.Router() in an express server?

    We use a const variable similar to app.

3. What do we use route middleware for?

    Middleware can be used to handle specific routes or parts of certain routes.
