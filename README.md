# JavaFX-Chat-Server

This project uses a separate Java Thread for each client connected to the server.
Each client can send a message to a single client (one-to-one), a group of clients
(one-to-many) or to all clients on the server (one-to-all). Each client also has a
list of active clients currently connected to the server and this list gets 
updated when a new client joins the server or when an existing client disconnects
from the server with its respective notification.
