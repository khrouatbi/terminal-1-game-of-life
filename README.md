Game of life multiplayer game has been implemented using the technologies listed.

What is missng to do is to:
Make a different colort for each player.
Add the pattern toolbar at the end.

For the parts 1-3 they have been fully implemented and deserve full grade.


This code is written by two other contributors.

I managed to make some changes to the design and functionalities.

To run on command prompt:
1. cd directory.
2. npm install
3. node app.js
4. go to localhost:3000

Works on Heroku.


## Server
- Node.JS
- Express
- socket.io

## files:

- `'/api/users/updateIsTyping'` :`socketId` and a `isTyping`.
- `'/api/messages/list'` : The messages
- `'/api/messages/submit'` : `socketId` parameter and a `body` parameter
- `'/api/messages/clear'` : `socketId`. Clears all messages.
- `'/api/grid/current'` : the current grid state
- `'/api/grid/start'` : Starts simulation
- `'/api/grid/pause'` : Pauses simulation
- `'/api/server/info'` : info about the server
- `'/api/users/list'` : connected users
- `'/api/users/rename'` :`socketId` and a `username`.

## Client
- Angular
- Angular's Boostrap UI
- socket.io
