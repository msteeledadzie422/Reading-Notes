# Introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.

    Middleware is a package that can be "plugged in" to a server to address web development problems. These are libraries that can work to handle things like cookies, sessions, user logins, URL parameters, POST data, security headers, and more.

2. Express the most popular __ __ ____.

    Express is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks.

3. Express is “unopinionated.” What does that mean?

    Express is unopinionated. You can instert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure.

4. What is a module and why is modularity useful to us as developers?

A module is a JavaScript library/file that you can import into other code using Node's require() function. Express isa module, as are other middleware and database libraries that are used in Express applications.

Modularity is useful because it allows us to organize code into manageable parts - a monolithic single-file application is hard to understand and maintain. Using modules also helps us manage our namespacee, because only the variables you explicitly exprt are imported when you use a module.
