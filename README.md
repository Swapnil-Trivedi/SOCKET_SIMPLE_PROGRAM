# SOCKET_SIMPLE_PROGRAM
The repository have data files for my server and client program in Python 3 for the deployment of a simple socket network.
Introduction
in the domain of network programming one of the major protocol is Transmission Control Protocol. A simple implementation of TCP
based connection is attempted with the help of Sockets.
Sockets are the endpoints of a bidirectional, point-to-point communication channel. Given an internet connection, say between client(a browser) and the server(say Google.com), we will have two sockets. A Client Socket and a Server Socket.
The data transmission take place only when a secure connection is established from both ends.

SERVER
The server program is implemented and showed in the simple_server.py above.

Major points to note from the script are:
1.A default TCP socket is initialized with name 's'
2.Port is set to '8085' by default and can be changed as per the availability of the port via OS
3.Once the connection is established a connection object and address is sent back to server.
4.Message from the server is send in an encoded form and the type of encoding used is 'Utf-8'

CLIENT
The client side program is stored in simple_client.py above.

Major points from the script are:
1.In a similar fashion to server script a socket object is created
2.The same port is targeted which is allocaated to server for the binding
3.connection is established and recived data is deccoded back for use.

All socket connections are closed once the data transmission is over.
