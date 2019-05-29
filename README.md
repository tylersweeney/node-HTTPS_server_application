# node-HTTPS_server_application
This application is meant to be similar to PHP's sysinfo function. Node's os module is consulted to give information about the server. This example can easily be extended to gather other pieces of data about the sever.

The "http.createServer" function creates an http.Server object. Because it is an Event Emitter, this can be written in another way to make that fact explicit.

The "request" event takes a function, which reveives "request" and "response" objexts. The "request" object has data from the web browser, while the "response" object is used to gather the data to be sent in the response. The "listen" function causes the server to start listening and arranging to dispatch an event for every request arriving from a web browser.
