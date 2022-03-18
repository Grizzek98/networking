# Overview

The purpose of this project was to learn the basic of networking. To accomplish this I attempted to create a server / client chatroom application. This allows multiple clients to connect to the server at the same time and send messages through the server to all other clients, respectively.

The server constantly listens for connections and messages from those who are connected. When a message is received, it is sent to all clients other than the one who sent the original message. At this time, connected clients must refresh their terminal to show the messages they've received from the server. I plan to implement listeners in the future that will refresh the terminal to show new messages when they're received if the user is not currently typing.

The user has the ability to choose a username.


[Software Demo Video](http://youtube.link.goes.here)

# Network Communication

This chat app works on a client / server framework. The server receives all incoming
messages and distributes them to other connected clients.

TCP connections are made using the SOCKSTREAM argument in the python 'socket' library.

Messages are encoded and decoded using utf-8. Message headers are sent so that recipients 
know the size of the incoming message.

# Development Environment

- Visual Studio Code
- Python 3.10.2
    - Socket library
    - Select library
    - Errno library
    - Sys library

# Useful Websites

* [Real Python](https://realpython.com/python-sockets/#application-protocol-header)
* [Youtube](https://www.youtube.com/watch?v=Lbfe3-v7yE0)

# Future Work

* Create listeners so that clients don't have to manually refresh to recieve messages.