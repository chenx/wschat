# WSChat 
Websocket Chatroom

By: X. Chen  
Created on: 3/18/2015  
Last modified: 5/12/2015  


About 
======

This package is a chatroom implemented using using python/autobahn/twisted websocket. 

This is extended from the previous broadcastdemo package, and will be a testing client for the gametheory server. 
The concept is to build a simplified and specific server, and a fully functioning client based on this. The client
can can be used to test the more complex and generic gametheory server.

Basically, it's a chatroom: when server is started, a client can connect to the server and join a room,
then send message to all other clients. 

This can be easily extended to other multi-user games, from 2 players to any number of players.


See <a href="https://github.com/chenx/wschat/blob/master/README">README</a> for more details.
