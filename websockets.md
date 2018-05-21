## Websocket in Node.js using Socket.io

### What is the best use case of the Websocket protocol?

    a. Chat
    b. Viewing football score for the past week match
    *c. Only a
    d. Both a and b
    e. None of the above

### Which **maybe not be** the best application of Websockets protocol?

    a. Ad hoc messaging
    b. Relaying a live feed/stream
    *c. A banking transaction where synchronization of events matter
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

### Which of these libraries can be used to implement websockets in Javascript/Node.js?

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
    
### Is there any limit on the number of open websocket connections per client per server port?

    a. There's no limit
    b. 10k connections
    *c. 64k connections
    d. None of the above

### What's the similarity between HTTP/2 and Websockets. Choose the correct statement(s).

    a. Both the protocols allow the server to push data to the client.
    b. Both maintain an open persistent connection with the client.
    c. HTTP/2 server push, likee websocket server push, is guaranteed to reach a client even with proxies and intermediaries in the middle.
    d. a, c
    *e. a, b
    f. All of the above.

### What is the major limiting factor for maximum number of open websocket connections on the server side?

    a. Limited number of available ports on the server 
    b. Available memory on the server 
    c. Limited number of file descriptors per socket
    d. None of the above

### What is the protocol scheme for secure websocket connection?

    a. ws
    *b. wss
    c. http
    d. https

### Which of pattern or patterns are used for implementing websockets in NodeJS?

    *a. Observer
    b. Reactor
    c. CSP
    d. Modules
	e. All of the Above
	f. None of the Above

### Which of these libraries can be used for websocket streaming?

    a. socket.io
    b. ws
    c. socket-stream
    *d. websocket-stream

### Which of the statement(s) is **FALSE** when comparing Websockets with HTTP?

    a. HTTP is uni-directional protocol, where, either a client or a server only can talk at a single instance of time.
    b. Websocket support full dulplex communication, where client and server can talk independently of each other.
    *c. HTTP is a lean protocol, not many headers are sent back and forth between a client and a server during a chat like application.
    d. Websocket keeps the tcp/ip connection open whereas HTTP closes it once the request/response cycle is over.

### Can websockets work behind a proxy server? Which of this below statement(s) is correct?

    a. Proxy server has to be configured separately to handle websocket traffic since a websocket data frame is an uknown entity to a http server.
    b. In case of direct connection, there won't be any problems since both the http ports 80 and 443 are open in most organizations. No speacial config required in that case.
    c. It always best to use wss:// scheme and establish encryted connection to bypass any intermediary proxy server.
    *d. All of the Above.
    e. None of the Above.
    