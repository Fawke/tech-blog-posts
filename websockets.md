## Websocket in Node.js using Socket.io

### What is the best use case of the Websocket protocol?

    a. Multimedia Chat
    b. Viewing football score of the past week match
    *c. Only a
    d. Both a and b
    e. None of the above

### Which **maybe not be** the best application of Websockets protocol?

    a. Ad hoc messaging
    b. Relaying a live feed/stream
    *c. Synchronized operation/or where sequence of operations matter
    d. Push notifications/instance updates

### How does the client establishes a websocket connection with the server?

    *a. client sends a GET HTTP request, with header containing connection: upgrade, and upgrade: websocket
    b. client sends a POST HTTP request, with connection: upgrade, and upgrade: websocket sent as a payload in request body
    c. client starts sending data frames directly to the server
    d. client can't initiate a websocket connection with the server

### Which used to be the best way of getting instant live updates from the server before Websockets became the de facto standard?

    *a. Long polling
    b. AJAX
    c. Polling
    d. All of the above.

### Which of these libraries can be used to implement for Javascript/Node.js?

    a. websocket
    b. socket.io
    c. clusterws
    d. ws
    *e. All the above libraries can be used to implement Websockets.

### How can we scale a websocket server horizontally?

    a. Spawn multiple socket servers to distribute the load.
    b. Put a load balancer in front to manage distribution across multiple spawned instances of socket servers.
    c. Apart frpm spawning multiple instance and putting a load balancer, we need a messaging channel to communicate between different spawned instances. 
    d. It's impossible to horizontall scale a websocket server.

### I want to send my chat message to all the connected clients to the socket server using socket.io library. I can achieve this by...

    a. socket.emit('myMessage', "hello");
    b. io.sockets.emit('myMessage', "hello");
    *c. socket.broadcast.emit('myMessage), "hello");
    d. socket.broadcast('myMessage', "hello");

### Which one of these events are **built in** on the client side which can be used for Error Handling?

    a. Connect
    b. Disconnect
    c. Error
    *d. All the above
    e. None of the above

### Which of these statement(s) **is FALSE** regarding namespaces in socket.io?

    a. It allows us to assign a endpoint/path to our url.
    b. It helps to minimize the number of TCP connections.
    *c. This feature is inherent in the Websocket protocol
    d. Within each namespace, you can also define arbitrary number of channels you can join or leave.

### Which statement **is TRUE** about websockets?

    a. It provides a full duplex communication.
    b. It streams messages on top of TCP
    c. Websocket protocol specification defines `ws` and `wss` as two new URI schemes.
    *d. All statements are true.
    e. None of the statements are true.
    
### limit of number of ws connections on server side.

### http 2 vs websockets

### maximum ws with server on the browser

### what is the protocol for secure ws connection

### what is the underlying design pattern that ws

### ws vs rest

### libraries for streaming data on websockets

### stateless vs stateful connections
