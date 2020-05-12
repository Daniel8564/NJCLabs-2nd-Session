# NJCLabs-2nd-Session
Q&amp;A of client/server and MicroServices

Client-Server
 
1.	Tell us about the features of client/server?

Client-server architecture is a computer network in which many clients (remote processors) request and receive service from centralised server (host computer)

2.	What is a Web server in a client server environment?

A web server processes incoming network request over HTTP and several other related protocols. The primary function of web server is to store, process and deliver web pages to clients. This communication takes place using HTTP

3.	What is the role of the presentation layer?

The presentation layer/tier is the front end layer in the 3-tier system and consists of the user interface. The user interface is usually a graphical syntax accessible through a web browser and which displays content and information useful for end user/client.

4.	They say this architecture is secure, how is it done in your opinion?
Secure architecture means that in each layer of 3-tier system, the firewall is implemented to secure the database. i.e. SSL certificate on the server to ensure the traffic is secure, or having a firewall set up between the server and client, or have a separate SQL DB Server.

5.	What is a Database Server in a client server environment?

A DB Server is a computer system that provides other computers with services related to accessing and receiving data from DB. Access to DB server may occur locally on user/client machine or remotely on the DB server which can be accessed by remote shell.

6.	What are Super servers in client server environments?

A super server starts other servers when needed. This can be ideal for workstations used for local web development or client/server development

7.	Explain 2-Tier and 3-Tier architecture?

2-Tier architecture is based on client server architecture and the communication between client and database occurs directly. This means there is not intermediate between client and server. Whereas in 3-Tier architecture there is a business layer between client and database. The 3-tier system has the advantageous of high performance, scalability, flexibility and security as the client is not directly connected to database.  

8.	What is a File server?

File server is a central server in a computer network that enables authorised connected clients to access server’s storage capacities. Accessed users can open, read, change and delete files and folders on a file server.
