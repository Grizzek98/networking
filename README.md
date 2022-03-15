# Overview

{Important!  Do not say in this section that this is college assignment.  Talk about what you are trying to accomplish as a software engineer to further your learning.}

{Provide a description the networking program that you wrote. Describe how to use your software.  If you did Client/Server, then you will need to describe how to start both.}

{Describe your purpose for writing this software.}

{Provide a link to your YouTube demonstration.  It should be a 4-5 minute demo of the software running (you will need to show two pieces of software running and communicating with each other) and a walkthrough of the code.}

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

{Make a list of websites that you found helpful in this project}
* [Real Python](https://realpython.com/python-sockets/#application-protocol-header)
* [Youtube](https://www.youtube.com/watch?v=Lbfe3-v7yE0)

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}
* Item 1
* Item 2
* Item 3