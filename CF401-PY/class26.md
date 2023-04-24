# Intro to Django

1. What are the key components of the Django framework, and how do they contribute to building a web application?

    In a traditional data-driven website, a web application waits for HTTP requests from the web browser (or other client). When a request is received the application works out what is needed based on the URL and possibly information in POST data or GET data. Depending on what is required it may then read or write information from a database or perform other tasks required to satisfy the request. The application will then return a response to the web browser, often dynamically creating an HTML page for the browser to display by inserting the retrieved data into placeholders in an HTML template.

    Django web applications typically group the code that handles each of these steps into separate files:

      *URLs:* While it is possible to process requests from every single URL via a single function, it is much more maintainable to write a separate view function to handle each resource. A URL mapper is used to redirect HTTP requests to the appropriate view based on the request URL. The URL mapper can also match particular patterns of strings or digits that appear in a URL and pass these to a view function as data.
      *View:* A view is a request handler function, which receives HTTP requests and returns HTTP responses. Views access the data needed to satisfy requests via models, and delegate the formatting of the response to templates.
      *Models:* Models are Python objects that define the structure of an application's data, and provide mechanisms to manage (add, modify, delete) and query records in the database.
      *Templates:* A template is a text file defining the structure or layout of a file (such as an HTML page), with placeholders used to represent actual content. A view can dynamically create an HTML page using an HTML template, populating it with data from a model. A template can be used to define the structure of any type of file; it doesn't have to be HTML!

2. Explain the role of Django’s MTV (Model-View-Template) architecture and how it handles a typical web request-response cycle.

    The MTV starts by sending the request to the right view. A URL mapper is typically stored ina file named urls.py. If an HTTP Request is received that has a URL matching a specified pattern, then the associated view function will be called and passed the request.
    
    The urlpatterns object is a list of path() and/or re_path() functions (Python lists are defined using square brackets, where items are separated by commas and may have an optional trailing comma. For example: [item1, item2, item3,]).
    The first argument to both methods is a route (pattern) that will be matched. The path() method uses angle brackets to define parts of a URL that will be captured and passed through to the view function as named arguments. The re_path() function uses a flexible pattern matching approach known as a regular expression. We'll talk about these in a later article!
    The second argument is another function that will be called when the pattern is matched. The notation views.book_detail indicates that the function is called book_detail() and can be found in a module called views (i.e. inside a file named views.py)

    Requests are handled using views.py. Views are the heart of the web application, receiving HTTP requests from web clients and returning HTTP responses. In between, they marshal the other resources of the framework to access databases, render templates, etc.
    Views are usually stored in a file called views.py.


3. What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?

    Tailwind CSS allows you to build and customize applications without writing custom CSS.

    Unlike Bootstrap, Tailwind is a low-level framework, meaning it does not offer fully styled components like buttons, dropdowns, and navbars. Instead, it offers utility classes so you cna create your own reusable components. This provies a lot more flexibility and control over what your application looks like than other CSS frameworks, allowing you to create a more unique site.
