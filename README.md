# Simple Chat Application Using Scokets

This is a simple chat application implemented in Java using sockets for communication between a client and a server.

## Overview

The project consists of two Java classes:
- **Client.java**: Represents the client-side code for the chat application.
- **Server.java**: Represents the server-side code for the chat application.

The client and server communicate with each other over a network using sockets. The client can send messages to the server, and the server can respond to those messages. The communication is bidirectional, allowing for real-time chatting between the client and the server.

## Features

- Real-time communication between client and server.
- Simple console-based interface.
- Support for multiple clients connecting to the server simultaneously.

## Usage

1. **Server Setup**:
   - Compile and run the `Server.java` file to start the server.
   - The server will start listening for incoming connections on port 7777.
   - ***Note:Here port 7777 is dummy port used in code.You can use any number according to your convenience.***


2. **Client Setup**:
   - Compile and run the `Client.java` file to start a client instance.
   - The client will connect to the server running on `127.0.0.1` (localhost) and port `7777`.

3. **Chatting**:
   - Once the client is connected to the server, you can start typing messages in the client's console.
   - The server will receive the messages and display them in its console.
   - Messages sent from the server will be displayed in the client's console.

4. **Termination**:
   - To exit the chat application, type "exit" in the client's console.
   - This will terminate the connection between the client and the server.

## Dependencies

This project does not have any external dependencies. It only relies on core Java libraries for networking and I/O operations.


