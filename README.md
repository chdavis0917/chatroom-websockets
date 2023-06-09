## Introduction

Welcome to the chatroom!

This is a simple chat web application based on WebSockets. The application supports one chat room, and users must provide a password that is validated on the server side before accessing the chat.

Once inside the chat, users can immediately send messages that will be displayed to other users. New users joining the chat will have access to a message history, although the history doesn't persist in case of a server restart.

In case of errors, users will receive a message, and the error will be logged on the server side. The backend for this project makes use of Go, while the frontend uses TypeScript/JavaScript.

Note: All references to main.js in this project are referencing a compiled JavaScript file generated by the TypeScript compiler (tsc).

## Instructions

Clone the repository from GitHub using:

```bash
 git clone https://github.com/chdavis0917/chatroom-websockets.git
 ```

Navigate to the cloned directory using:
```bash
cd chatroom-websockets
```

Install Typescript locally by running:
```bash
npm install
```

Make sure you have Go version 1.16 or higher installed on your machine.

Install the dependencies by running:
```bash 
go mod download
```

Start the server in the root directory by running:
```bash
go run server/websocket_server.go
```

Open your web browser and go to http://localhost:8080 to access the chat application.

Enter the password "pw" to access the chatroom.

Open localhost:8080 in another tab or window to see a history of messages from other users.

See live chat updates from other users in the chat room!
