# Tweeter
This is a Node.Js project made with the implementation of web framework Express API Routes.
## Getting Started
To run the application
```bash
npm run start
# or
node app.js
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

To Enter, Register first on the Register page or else Login on the Login page with the Username and Password used during Registration.

## Implementation
Pug has been used as template engine for Node and for the browser. Pug makes it easy both to write reusable HTML, as well as to render data pulled from a database or API.
To install Pug
```bash
$ npm install pug
```
To install Socket.IO
```bash
$ npm install socket.io
```
Node.js has been used in the backend.

For storage and retrieval of data noSQL database MongoDB has been used.

## Features
Provides all the essential features of Twitter with the Search facility of Users and Posts.

Added feature of getting Notifications Popup at the top to aware the User of who have Followed or Messaged the User in Realtime.

Feature of Group chatting along with personal chat have been provided with the help of SOCKET.IO.

Passwords are protected with multiple rounds of hashing with the help of bcrypt.js.

## Learn More

To learn more about Pug, Socket.IO, take a look at the following resources:
- [Pugjs](https://pugjs.org/api/getting-started.html) - learn about Implementation, features and API.
- [Socket.IO](https://socket.io/get-started/chat) - learn about Implementation, features and API.
