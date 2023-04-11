# Web Scraping

1. What are the key differences between scraping static and dynamic websites?
      A dynamic website is a type of website that can update or load content after the initial HTML load. So the browser receives basic HTML with JS and then loads content using received Javascript code. Such an approach allows increasing page load speed and prevents reloading the same layout each time you'd like to open a new page.
      In contrast to dynamic websites, we can observe static websites containing all the requested content on the page load.
      

2. Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.
      1. Respect Robots.txt: Web spiders should ideally follow the robot.txt file for a website while scraping. It has specific rules for good behavior, such as how frequently you can scrape, which pages allow scraping, and which ones you can’t. Some websites allow Google to scrape their websites, by not allowing any other websites to scrape. This goes against the open nature of the Internet and may not seem fair, but the owners of the website are within their rights to resort to such behavior. 
      2. Make the crawling slower, do not slam the server, treat websites nicely: The faster you crawl, the worse it is for everyone. If a website gets too many requests than it can handle it might become unresponsive. Make your spider look real, by mimicking human actions. Put some random programmatic sleep calls in between requests, add some delays after crawling a small number of pages and choose the lowest number of concurrent requests possible. Ideally, put a delay of 10-20 seconds between clicks and not put much load on the website, treating the website nice.
      3. Do not follow the same crawling pattern: Humans generally will not perform repetitive tasks as they browse through a site with random actions. Web scraping bots tend to have the same crawling pattern because they are programmed that way unless specified. Sites that have intelligent anti-crawling mechanisms can easily detect spiders by finding patterns in their actions and can lead to web scraping getting blocked. Incorporate some random clicks on the page, mouse movements and random actions that will make a spider look like a human.


3. What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.
      Playwright can be considered as an extended Puppeteer, as it allows using more browser types (Chromium, Firefox, and Webkit) to automate modern web app testing and scraping. You can use Playwright API in JavaScript & TypeScript, Python, C# and, Java. And it's excellent, as the original Playwright maintainers support Python.
      The API is almost the same as for Pyppeteer, but have sync and async version both.

      An example use case of when Paywright is especially beneficial is when conducting automated testing. Playwright is an automated testing tool that mimics the actions of a manual tester. By automatically generating test scripts, Playwright helps reduce the time and effort required to test.


4. Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.
      XPath stands for XML Path. It is W3C recommended technique used to identify and navigate nodes in an XML document. In automation, we use XPath to find elements on a webpage.
      XPath selectors are equivalent to calling Document.evaluate(), where evaluate() is a method of the Document interface that selects elements based on the XPath expression given in parameters.

      You would usee //h1 to select an h1 HTLM element from the webpage.
