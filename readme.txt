eXtended Time Strategy :)

RTS modules (scheduled and on demand) operate on server hosted loops.
State machines store data values to describe aspects of the game, including score and schedules. 
State Machine data values can be updated through standard communications and a CRUD-based application, enabling extended time.

Development Phase 1

Two servers: RTS_proto and XTS_proto. Both hosted on a Java platform for now, probably running on a Raspberry Pi. But I'm also thinking
about using my cloud server. The one that runs parrot.nigeldeans.com. That way I don't have to worry about the firewall and now that I 
remember, Jelastic has Git integration features. 


RTS server

Just build a sample game from a simple tutorial, but one that relects the principal of real time play... 
something like Tetris or Space Invader. Or we can even deploy a game of there's something open source. Just need something real 
that running so we can test integration. 

XTS listener

A simple CRUD application featuring an inbox. Maybe also a set of functions exposed through REST.
An associated email account, maybe on Google. This project is already set up as SMM (State Machine Module)



Client Application: XTSClient. Downloadable from XTS_proto

1. Authentication/Authorization
2. Set of commands for reading and writing data to and from XTS_proto








