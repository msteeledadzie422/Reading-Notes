# Event Driven Programming

_1. What native Node.js module allows us to get started with Event Driven Programming?_

  Node.js natively provides us with a useful module called EventEmitter that allows us to get started with Event Driven Programming.


_2. What is the value of Object Oriented Programming used in tandem with Event Driven Programming?_

  By registering event listeners we can actually reverse the flow of communication between our objects. Rather than an object needing to "reach inside" another object to trigger a function, our objects can just emit events and whichever objects are listening to those events will process it in the way they have been told to. The source of an objects behavior is now entirely contained within itself, rather than needing to be accessed by external objects. 


_3. Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js._

  Event Driven Programming is useful in the backend because it allows us to keep everything self-contained. All events can be handled and all objects can communicate with each other within the server and then send the necessary response to the Browser, rather than the Browser needing to take in an event, send a request to the server for the server to then do the necessary event handling work before sending back a response. Containing everything within the server keeps things efficient and secure.
  
