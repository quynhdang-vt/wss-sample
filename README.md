
## Sample of a websocket client - server


### Server 

HTTP endpoints:
    
  * `/wss/`  <-- for websocket communications 
  * `/general/` <-- for non-wss to interact indirectly with the wss clients, eg. list all clients, post a message to a client given its ids


### WSS client

 Will go tto the /wss/ endpoint at first then :

 * PostMessage <- given a message of certain json schema
 * ReadMessage <- from server and provide handlers


Must support multi-clients


See samples:

https://yalantis.com/blog/how-to-build-websockets-in-go/

https://tutorialedge.net/projects/chat-system-in-go-and-react/part-4-handling-multiple-clients/#websocketgo 

