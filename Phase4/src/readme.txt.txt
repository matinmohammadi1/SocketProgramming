# Member : Aryas Zandkarimi & Matin Mohammadi

# program language : Java

# GitHub links : https://github.com/AryasZandkarimi90 && https://github.com/matinmohammadi1


# Java Socket Chat Application

A simple multi-client chat application built in Java using sockets, supporting public and private messaging, username display, and a graphical client.

----------------------------------------------------------------------------

## Features

-- **Server** that handles multiple clients concurrently via threads.
-- **Public messages** broadcasted to all connected clients.
-- **Private messaging** using a simple command:

-  **Username support** in the graphical client.
-  **Timestamp and username display** with each message (in the GUI client).
-  **Graphical client (Swing-based)** and **Console client** available.
-  **Automatic removal of disconnected clients**.
-  **Error handling and connection stability improvements**.

------------------------------------------------------------------------------

## Run the server

Server will start listening on port 1234.


## Run the clients


## GUI-based client: It will prompt for a username and open a chat window.


Commands :

✅ Public Message :
Just type your message and hit Enter — everyone will receive it.

✅ Private Message :
To send a private message: >pm <clientIp> <your message>


## Example :

>pm /127.0.0.1 Hello, this is private!

You can find client IP addresses in the server console logs when clients connect.

## Exit
Type: /exit

To gracefully leave the chat.


------------------------------------------------------------------------------------

# End Of File




