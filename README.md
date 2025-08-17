## Real-Time Collaborative Document Editor (Collab-Editor)

A real-time doc editor built with Node.js, WebSockets, and React—because jumping into code with others shouldn’t feel like herding cats.

--------------------
## What’s This About?

Collab-Editor lets multiple people edit the same document at the same time. Changes flow instantly thanks to WebSockets, and the React front-end updates in real time. It runs locally, making testing and collaboration a breeze.

----------------------
## Why Does It Exist?

Want to experiment with real-time apps?

Need a base for a team collaboration tool?

Just curious how WebSockets and React dance together?

This project shows it all in action.

----------------

## Features


Real-time editing across multiple users.

Easy to set up and run locally.

Simple tech stack for readability and tinkering.

-----------------

## Tech Stack

Backend: Node.js server with express, ws, and cors.

Frontend: React app using WebSocket client.

Communication: WebSocket bridges changes between clients.

-----------------

## Quick Start

Clone the repo:

git clone https://github.com/om-ganechari/.-Real-Time-Collaborative-Document-Editor.git

------------------------------------------


##  Install dependencies:

npm install

-----------------------------


Launch your server:

npm start
# or if entry file is server.js:
node server.js


Open http://localhost:3000 in a few browser windows/tabs.

Type in one window—watch the others keep up in real time.

--------------------------

## How It Works ?

When you type, your changes ship to the server via WebSockets. The server broadcasts to everyone else; the frontend receives it, updates the state, and bam—everyone sees the same doc at the same time.

------------------------------

## Structure
/
├── client/           # React app
│   ├── src/
│   └── public/
├── server.js         # Express + WebSocket server
├── package.json
└── README.md


--------------------------------



License

MIT—do your thing, just don’t hold the author liable.
