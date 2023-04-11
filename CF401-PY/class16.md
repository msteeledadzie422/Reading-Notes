# What is Serverless Computing

1. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?
      'Serverless' describes the developer’s experience with those servers—they are are invisible to the developer, who doesn't see them, manage them, or interact with them in any way.
      
      Serverless lets developers put all their focus into writing the best front-end application code and business logic they can. All developers need to do is write their application code and deploy it to containers managed by a cloud service provider. 
      The cloud provider handles the rest, provisioning the cloud infrastructure required to run the code and scaling the infrastructure up and down on demand as needed. The cloud provider is also responsible for all routine infrastructure management and maintenance such as operating system updates and patches, security management, capacity planning, system monitoring and more.


2. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?
      You can import a project by connecting it to an existing repository in GitHub.
      
      1. On the "New Project" page, under the "Import Git Repository" section, choose the account that you'd like to link a project from.
      2. Find the repository in the list and select Import.
      3. Vercel will automatically detect the framework and any necessary build settings. However, you can also configure the Project settings at this point including the build and development settings and Environment Variables. These can also be set later.
      4. Press the Deploy button. Vercel will create the Project and deploy it based on the chosen configurations.
      5. Enjoy the confetti!

      To view your deployment, click on the Project in the dashboard and then click on the Domain. This page is now visible to anyone who has the URL.


3. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?
      API stands for application programming interface. In essence, an API acts as a communication layer, or as the name says, an interface, that allows different systems to talk to each other without having to understand exactly what each other does.
      APIs can come in many forms or shapes. They can be operating system APIs, used for actions like turning on your camera and audio for joining a Zoom call. Or they can be web APIs, used for web-focused actions such as liking images on your Instagram or fetching the latest tweets.

      With API calls you can perform actions such as:
      * Searching and fetching GIFs
      * Getting COVID-19 confirmed cases per country
      * Searching Google Books


4. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?
      Requests allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.
