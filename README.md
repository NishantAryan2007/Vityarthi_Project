# Java Multi-User Chat

A lightweight Java chat app for real-time group messaging. It includes a server, a command-line client, and a Swing-based GUI client, supporting multiple users with unique usernames and basic chat commands.

## What's Included

- *Server*: Manages client connections and message broadcasting (ChatServer.java).
- *CLI Client*: Text-based interface for chatting (ChatClient.java).
- *GUI Client*: Graphical interface with chat and user list (ChatClientGUI.java).
- *Client Handler*: Processes individual client actions (ClientHandler.java).
- *Launcher*: Starts the server or CLI client (ChatApplication.java).

## Key Features

- Multi-user real-time chat with concurrent connections.
- Commands: /help (list commands), /users (show online users), /quit (exit).
- Unique username registration for each client.
- Thread-safe design using ConcurrentHashMap.

## Requirements

- Java Development Kit (JDK) 8+.
- Terminal or IDE (e.g., VS Code, IntelliJ) for compilation.
