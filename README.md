# chat-application
This repository contains a fully functional private chat application using MongoDB, Socket.io and Express that supports real-time chatting and also allows to retrieve chat when logged in later.

## Tech-stack -
- HTML, CSS (for front-end interface)
- JavaScript (both front-end behaviour and in the back-end)
- Node.js and Express.js (for back-end server)
- Socket.io (for real-time interaction between the client and the server)
- MongoDB (as database to store chats, online users etc.)
## Usage Guide -

1. Install [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) on your system. Check using the following commands in the terminal -

```cmd
$ node -v
$ mongod --version
```

2. Open your terminal and run the following -

```cmd
$ git clone https://github.com/Vinaythavisi/chat-application/
$ cd chat-application
$ npm install
$ node server.js
```

3. Now, the server is running, open the link http://localhost:5000/chat.html to access the chat interface

4. Type your name and the 2nd person name and press done to establish a connection. You will see the entire chat history retrieved between the two people.

5. Open the same URL in another browser/tab and establish the other half of the connection

6. Send messages from any end to see the functioning

7. Close when you have to exit the chat 

Feel free to try different cases, like when one user is offline, when both users are online but one of them is chatting with other person, etc.
