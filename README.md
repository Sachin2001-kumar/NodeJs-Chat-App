# NodeJs-Chat-App

Overview
This is a simple chat application built using Socket.IO for real-time communication between clients and a server.

Files Included
client.js: Handles client-side operations such as sending messages, receiving messages, and updating the UI dynamically.
index.js: Server-side script using Node.js and Socket.IO to manage connections, messages, and user interactions.
index.html: The main HTML file providing the structure and interface for the chat application.
style.css: CSS file for styling the chat interface.
Dependencies
Node.js: Ensure Node.js is installed on your system.
Socket.IO: Dependency for real-time, bidirectional event-based communication.

How to Run
Clone the repository to your local machine.
bash
git clone <repository-url>
cd <repository-directory>
Install dependencies using npm.

npm install
Start the server.

node index.js
The server will start at http://localhost:8000.

Open index.html in a web browser. Ensure your browser supports WebSocket connections.

Enter your name when prompted to join the chat.

Features
Real-time Messaging: Messages are sent and received instantly using Socket.IO.
User Join/Leave Notifications: Notifies users when someone joins or leaves the chat.
Audio Notification: Plays a notification sound when a new message is received.
Usage
Type your message in the input field and press "Send" or hit Enter to send it.
Messages you send appear on the right side, and messages received from other users appear on the left.
Customization
Modify style.css to change the look and feel of the chat interface.
Update ting.mp3 with your preferred notification sound.
Notes
This application is intended for learning purposes and may require additional features for production use (e.g., user authentication, message persistence).
