# Introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.

    Middleware is a package that can be "plugged in" to a server to address web development problems. These are libraries that can work to handle things       like cookies, sessions, user logins, URL parameters, POST data, security headers, and more.

2. Express the most popular __ __ ____.

    Express is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks.

3. Express is “unopinionated.” What does that mean?

    Express is unopinionated. You can instert almost any compatible middleware you like into the request handling chain, in almost any order you like. You     can structure the app in one file or multiple files, and using any directory structure.

4. What is a module and why is modularity useful to us as developers?

    A module is a JavaScript library/file that you can import into other code using Node's require() function. Express isa module, as are other middleware     and database libraries that are used in Express applications.

    Modularity is useful because it allows us to organize code into manageable parts - a monolithic single-file application is hard to understand and           maintain. Using modules also helps us manage our namespacee, because only the variables you explicitly exprt are imported when you use a module.

# What is NPM

1. What version of npm are you running on your machine?

    npm version 18.9.0

2. What command would you type to install a library/package called ‘jshint’ into your node project?

    npm install jshint

# What is TDD

1. Explain why tests are important. Please explain as though I were your non technical elder.

    They allow us to ensure our code passes the simplicity criteria.

2. What are three expected benefits of testing

    - Many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
    - The same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
    - Although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code,       and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.


# CI/CD

1. What are three benefits of Continuous Integration?
    
    Ensure everyone's changes integrate
    Catch bugs
    Reduce merge conflicts

2. What is the difference between Continuos Delivery and Continuous Deployment?

    Continuous Delivery is the process of writing code in such a way that it could be deployed at any time.
    Continuous Deployment is an extension of Continuous Delivery. It's a process that allows you to actually deploy newly developed features into               production with confidence and experience littly to any downtime.

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background

    GitHub is like a clearinghouse for your code. Developers make changes locally and push those changes to GitHub when they want to share them with           others. 
