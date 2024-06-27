Chat Server and Client with Admin Control

This project implements a multi-client chat application where clients can connect to a server and exchange messages. The server supports basic chat functionalities such as sending messages to all connected clients. Additionally, it includes admin controls allowing the admin user to kick and ban other clients from the chat.

Key Features:

Server: Listens for incoming client connections and manages client interactions.
Client: Connects to the server, sends messages to the chat, and receives messages from other clients.
Admin Controls: Admin users can kick users out of the chat and ban them from reconnecting.
Instructions:

Run the server on a machine accessible to all clients.
Clients connect using their chosen nicknames and can chat with other connected clients.
Admins can execute /kick <nickname> and /ban <nickname> commands to manage users.
Technologies Used: Python, Socket Programming, Threading