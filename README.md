A Working Genshin Impact private server hosted in your own pc.

 WARNING
* Please use a [VPN](https://en.wikipedia.org/wiki/Virtual_private_network) or a [Virtual Machine](https://en.wikipedia.org/wiki/Virtual_machine) while you test this project, the fiddler script should block all the logs to mihoyo's server but im not sure at all, please use this project with caution (I havent been banned for now but that doesnt mean you're not taking the risk to get banned)

# Installation
The installation assumes you have installed the next things in your pc
* [git](https://git-scm.com/downloads)
* [node-js](https://nodejs.org/en/download/) 
* [Fiddler](https://www.telerik.com/download/fiddler) you can use host file

In case you dont have them, please install them otherwise you would not be able to start the server.
## Project (The Server itself)

1. Run modules.bat to install the required modules
1. You can now open the project in your IDE

## Fiddler (Traffic Redirector)
1. Open fiddler and go to FiddlerScripts

1. Copy fiddler.cs content and paste it into fiddler
1. Press Save Script button


Now open Genshin Impact and have fun.
# Information
Im making this project to learn how to reverse data sent by the client to the server, i will work in this if i feel motivated enough to work on it, the project will be private and only me and some friends will be able to see/know about it.

# How To Play
1. Open Fiddler
1. Double click start.bat
WARNING
Do not close Fiddler or the console if you want to play in the server

For now, you can only login using a non-existent email and password.

# TODO
* Login

* KCP Packet Handler
no image
* Announcements

# Work In Progress
Be able to use other char 

# Modules Used
Modules used for this project, will be adding more.
* net - TCP Server
* http - HTTP Server
* dgram - UDP Server
* node-kcp - KCP Server
* protobuff-js - Protobuff encoding
* sqlite3 - Database reading
* udp-proxy - works as a sniffer
