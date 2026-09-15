# Real-Time Chat Application

A real-time messaging web app built with Node.js, Express, and Socket.io — messages appear instantly for all connected users without page reloads.

## Features
- Real-time bidirectional messaging using WebSockets (Socket.io)
- Multiple users can join and chat simultaneously
- Simple, responsive chat UI

## Tech Stack
- **Backend:** Node.js, Express
- **Real-time communication:** Socket.io
- **Frontend:** HTML, CSS, JavaScript

## Project Structure
```
Real-Time-chat-application-using-socketio-chat/
├── public/          # Frontend files (HTML/CSS/JS)
├── index.js         # Express + Socket.io server
├── package.json
└── README.md
```

## Getting Started

### Prerequisites
- Node.js installed

### Setup
```bash
git clone https://github.com/Bhuvana-sketch/Real-Time-chat-application-using-socketio-chat.git
cd Real-Time-chat-application-using-socketio-chat
npm install
npm start
```

Then open `http://localhost:3000` (or whichever port is configured) in your browser. Open it in multiple tabs to see real-time messaging in action.

## What I learned
- Setting up WebSocket connections with Socket.io for real-time, two-way communication
- Structuring an Express server to serve both static frontend files and handle socket events
- Managing multiple connected clients and broadcasting messages

## Future Improvements
- User authentication and usernames
- Persistent chat history (MongoDB)
- Typing indicators and read receipts
