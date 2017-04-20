# WebSocketSample

Here's a web socket sample of both client(iOS) and server side(node.js).
Based on [this tutorial](http://www.appcoda.com/socket-io-chat-app/), I fixed some issues in both sides and update to Swift 3.

### Requirement

- Node.js: https://nodejs.org/en/.
- Express, Web framework of node.js: `npm install --save express@4.15.2`.
- Xcode 8.0+. :P

### Steps

- Run server:

```
$ cd WebSocketSample/ServerWebSocket
$ node index.js
```
Open `http://localhost:3000` in browser.

- Run client:

```
$ cd WebSocketSample/ClientWebSocket
$ open SocketChat.xcodeproj
```

### Result

- iOS simulator can talk with browser part.


### TODO

- In server part, chat history doesn't show in browser, which means, you can only see the sended message in terminal and client part.
- In server part, username is hard-coded at present.
