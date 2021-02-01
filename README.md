# Install Virtual Network and Test Web Application
In this project, I created one virtual system where I installed five machines for testing web application.

Two of them are working as a client machine where we installed Windows 10 and Windows 8.1 operating system. Using this machine we navigate to website which is hosted on the web server.

Other 3 machines are servers where I installed Microsoft Server 2012, one machine acts as a web server (SVR-WS-A-1913083) where I installed PHP and MySQL Workbench and then hosted a web application on the server. The other one works as a router (SVR-SO-A-1913083) which is help to connect devices within a network and send or receive data to and from each other by using local IP addresses. And, the last one is a domain controller (SVR-DC-A-1913083) for the authentication and validating client requests on the network.


When virtual environment was built successfully, I started testing a web application from client machines. Tested web application by three functional phases of testing and one non-functional phase of testing.
1.	Unit Testing
2.	Integration Testing
3.	System Testing
4.	Non-functional Testing


## Project Scope
- Create a network environment of 5 systems on VirtualBox
- The environment consists of 3 servers and 2 clients
- Three Servers:
  1. Router
  2. Domain Controller
  3. Web Server
- Two Clients:
  1. Client 1 - Windows 10
  2. Client 2 - Windows 8.1
- Host a web application on web server and access it from client machines
- Test the connectivity of whole network
- Test the hosted web application
