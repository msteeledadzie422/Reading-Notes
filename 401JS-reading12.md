# Web Sockets

_1. What is a Web Socket?_ 

  A WebSocket is a computer communications protocol, providing full-duplex communication challens over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011. The current API specification allowing web applications to use this protocol is known as WebSockets.


_2. Describe the Web Socket request/response handshake and what happens once the connection is established._ 

  To establish a WebSocket connectin, the client sends a WebSocket handshake request, for which the server returns a WebSocket handhake response.
  
  The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidrectional binary protocol which does not conform to the HTTP protocol.
  

_3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client._

  WebSockets provide a standardized way for the server to send content to a client without first receiving a request from that client, and allowing messages to be passed back and forth while keeping the connection open. In this way, a two-way ongoing conversation can take place between the client and the server.


# Socket.io Tutorial

_1. What does the event handler io.on() do?_

  The io.on event handler handles connection, disconnection, etc., events in it, using the socket object.


_2. Describe some possible proof of life or proof that the code works as expected_

  The require('socket.io')(http) creates a new socket.io instance attached to the http server and the io.on event handler handles connection, disconnection, etc., events in it, using the socket object.

  For proof of life you can use io.on to console.log an event such as whenever a user logs on to or off of your page. 


_3. What does socket.emit() do?_

  socket.emit will broadcast an event to all clients.


# Socket.io vs Web Sockets

_1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0)._

  WebSocket is the communication protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they all real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the client or server to terminate the request.

  Socket.IO is a library that enables real-time and full-duplex communcation between the Client and the Web servers. It uses the WebSocket protocol to provide the interface 
  
  WebSocket is the technology, while Socket.io is a library for WebSockets.

_2. When would you use Socket.IO?_

  To handle the degradation of your technical alternatives to get full-duplez communication in real-time.
  

_3. When would you use WebSockets?_

  When you need full-duplex communcation between the client and the server.


# OSI Model Explained

_1. What are a couple of key takeaways from this video?_ 

  - The Open Systems Interconnection model (OSI model) is a conceptual model that 'provides a common basis for the coordination of [ISO] standards development for the purpose of systems interconnection'
  - The model partitions the flow of data in a communication system into seven abstraction layers, to describe networked communication from the physical implementation of transmitting bits across a communications medium to the highest-level representation of data of a distributed application. Each intermediate layer serves a class of functionality to the layer above it and is served by the layer below it
  - Each layer in the OSI model has its own well-defined functions, and the functions of each layer communicate and interact with the layers immediately above and below it, unless the layer does not have layers below or above


# TCP Handshakes Explained

_1. Translate the gist of this video to a non-technical friend_ 

  TCP is a reliable and connection-oriented transport protocol. With TCP, data can be delivered successfully and accurately. 
  
  Before TCP transmits data, it will use a three-way handshake to establish a connection. Many applications you use such as web, email, and FTP use TCP.
