# Basic-computer-networking

A computer network is a system of two or more computers that are connected together to share resources. Networks can be as small as two computers in a home office or as large as the Internet. One computer acts as the server while the others act as the clients.

A server provides services to clients. The client is a personal computer or laptop that accesses services made available by the server.

Protocols are rules that dictate how data should be transmitted, and port numbers are used to identify specific software applications. Together, these two things ensure that the data you send or receive is delivered to the correct application.

To simulate a client and server communicating with each other, I used Cisco Packet Tracer. First, I added a laptop and a server to my topology. Then, I connected them together using a cross-over cable. A cross-over cable allows two computers to communicate directly with each other.

For two computers to communicate with each other, they need to have both an IP address and a MAC address. For this reason, I assigned IP addresses to the client and server.

To ensure a connection was established between the two computers, I pinged the server from the client computer using the ping command. Then, I accessed the web server from the client's computer web browser.

When I turned off the HTTPS service on my server, I found that I could no longer access the web page from my client's computer. This happened because the server was no longer listening on port 443.
