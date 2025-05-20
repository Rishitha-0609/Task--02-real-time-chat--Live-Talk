# Task--02-real-time-chat--Live-Talk
messages from client to server and vise varsa

A simple real-time chat application built with **Node.js**, **Express**, **Socket.IO**, and basic **HTML/CSS/JS**.

## 🚀 Features

- Real-time message broadcasting using WebSockets
- Simple and responsive chat UI
- Messages are visible to all connected users
- Clean UI with basic CSS styling
## install node.js latest version
Go to the official Node.js download page

Download the LTS version (recommended for most users)

Run the installer and follow the setup steps:

Accept license agreement

Choose installation location

Enable "Add to PATH"

After installation, open Command Prompt and verify:

node -v
npm -v

## Install all dependencies
npm install
npm install express@4
npm install socket.io
npm install sqlite sqlite3
npm install @socket.io/cluster-adapter

# run project
npx nodemon index.js
or 
node index.js
 
it runs in local server
http://localhost:9000
--->open this in two different tabs so that we can see the messages between client and server


## to Install nodemon globally if you want to run project using npx nodemon index.js

For auto-reloading your server on changes:
npm install -g nodemon

Then you can run your app using:
nodemon index.js

(Note:refer https://socket.io/docs/v4/tutorial/introduction for better understanding that how to  built this project)
