# Simple PHP Chat using WebSocket


A simple chat application using WebSocket and PHP socket programming. The WebSocket is used to create a bridge to send or receive messages from the PHP chat server.

For establishing a socket connection between the client and the server, we use the WebSocket protocol (ws://) to specify the address of the PHP page where the WebSocket handshake is handled. After creating WebSocket there are callbacks to handle the events that occur between the client and the server during the chat process.
