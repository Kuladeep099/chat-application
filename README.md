Description:
This project is a real-time chat application built using Node.js, Express, and Socket.IO. It enables users to exchange messages instantly across multiple browser sessions or devices. The application demonstrates full-stack integration with live, event-driven communication powered by WebSockets (via Socket.IO).

The project serves as a hands-on implementation of WebSocket-based technology and helps understand how real-time data transfer works on the web.

💡 Features:
Real-time bi-directional messaging

Multiple users can chat simultaneously

Automatically updates all clients on new messages

Simple, responsive user interface

Built-in auto-scroll for chat history

🧰 Tech Stack:
Component	Technology
Frontend	HTML, CSS, JavaScript
Backend	Node.js + Express
Real-Time Engine	Socket.IO
Platform	Localhost (can be deployed)

📁 Folder Structure:
php
Copy
Edit
realtime-chat-app/
├── server.js             # Main server file (Node + Express + Socket.IO)
├── package.json          # NPM config & dependencies
└── public/
    ├── index.html        # Frontend chat interface
    └── script.js         # Socket.IO client-side logic
🚀 How It Works:
The server (Node.js + Socket.IO) listens for new connections.

Clients (browsers) connect via Socket.IO.

When a user sends a message, the server broadcasts it to all connected clients.

All clients instantly see the new message without refreshing the page.

✅ How to Run:
Install dependencies:

bash
Copy
Edit
npm install
Start the server:

bash
Copy
Edit
node server.js
Open browser at:

arduino
Copy
Edit
http://localhost:3000
📦 Deliverables:
Full working code with frontend + backend integration

Real-time message broadcast using WebSockets

Structured folder with server.js, index.html, script.js

output:

<img width="1917" height="747" alt="Image" src="https://github.com/user-attachments/assets/002acba7-4965-49c0-8965-b39cf861f562" />
