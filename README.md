# Overview

This is my tutorial for a client-server network. Client-server is when a computer communicates directly to another computer without going through a server. This project was very challenging and forced me to learn a lot about networking.

The goal for this project was to start a server on the host computer and then clients can connect. Opon entering the chat you are prompted to enter a nickname. Once there is more than one client on the server then you can just type what you want and hit 'Enter'. Hopefully that is all the program will need.

[Software Demo Video](https://youtu.be/YkoVx_4YuRc)

# Network Communication

My program is a client-server network meaning that you need to start a server before any clients are able to connect.

The simplest type of connection is UDP so that is what I chose to do. This is faster than a TCP but is not guaranteed transfers. The port numebr I used is "55555".

# Development Environment

* Python
* Extention "threading"
* Extention "socket"

# Useful Websites

* [Peer to Peer Computing](https://www.tutorialspoint.com/Peer-to-Peer-Computing)
* [pyp2p * PyPl](https://pypi.org/project/pyp2p/)
* [What's the Difference Between TCP and UDP?](https://www.howtogeek.com/190014/htg-explains-what-is-the-difference-between-tcp-and-udp/)

# Future Work

* Add GUI
* Perhaps switch to peer-to-peer so there is no need to set up a server
* Add while loops so that if anything goes wrong it wont shut down
