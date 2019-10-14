# Improvements made to Socket.IO Chat

- Chat Messages now are displayed in bottom area (on top of the input box).
- When sending chat messages, older chat messages go further up (instead down), newest messages appear always on top of the input box (whatsapp behaivor).
- The input field and its font size has been enlarged.

# Socket.IO Chat

A simple chat demo for socket.io

## How to use

```
$ cd socket.io
$ npm install
$ cd examples/chat
$ npm install
$ npm start
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves
the chatroom.
