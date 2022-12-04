# Socket.io Chat Example

_1. Explain to a non-technical recruiter what the Chat Example (above) does._

  The Chat Example provides a bi-directional communication channel between a client and a server. This means that the server can push messages to clients. Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients.
  

_2. What proof of life are we getting on the backend from the above app?_ 

  We are getting Hello World  
  

_3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?_

  If you are looking to send a message to everyone except for a certain emitting socket, we have the broadcast flag for emitting from that socket.


# Rooms

_1. What is a room and how might a room be useful?_

  A room is an arbitrary channel that sockets can join and leave. A room is useful because it can be used to broadcast events to a subset of clients. 


_2. How do you join a room?_ 

  You can call join to subscribe the socket to a given channel and then simply use to or in (they are the interchangeable) when broadcasting or emitting.


_3. how do you leave a room?_

  To leave a channel you call leave in the same fashion as join.


# Namespaces

_1. What is a Namespace and what does it allow you to do?_

  A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection. This is also called "multiplexing."


_2. Each namespace potentially has its own what? (hint: 3 things)_

  Each namespace has its own 1/ event handlers, 2/ rooms, 3/ middlewares.


_3. Discuss a possible use case for separate namespaces_

  1/ You want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application.
