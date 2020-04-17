# SOCKET_SIMPLE_PROGRAM
#### The repository have data files for my server and client program in Python 3 for the deployment of a simple socket network.
## INTODUCTION
In the domain of network programming one of the major protocol is Transmission Control Protocol. A simple implementation of TCP based connection is attempted with the help of Sockets.
Sockets are the endpoints of a bidirectional, point-to-point communication channel. Given an internet connection, say between client(a browser) and the server(say Google.com), we will have two sockets. A Client Socket and a Server Socket.
The data transmission take place only when a secure connection is established from both ends.

## SERVER
The server program is implemented and showed in the simple_server.py above.

### Major points to note from "simple_server.py" script are:
- A default TCP socket is initialized with name 's'
- Port is set to '8085' by default and can be changed as per the availability of the port via OS
- Once the connection is established a connection object and address is sent back to server.
- Message from the server is send in an encoded form and the type of encoding used is 'Utf-8'

## CLIENT
The client side program is stored in simple_client.py above.

### Major points to note from "simple_client.py" script are:
- In a similar fashion to server script a socket object is created
- The same port is targeted which is allocaated to server for the binding
- connection is established and recived data is deccoded back for use.

All socket connections are closed once the data transmission is over.
