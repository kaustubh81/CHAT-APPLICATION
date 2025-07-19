# CHAT-APPLICATION

COMPANY : CODTECH IT SOLUTUONS

NAME : KAUSTUBH HASTAK

INTERN ID : CT08DL826

DOMAIN : FULL STACK DEVLOPMENT

DURATION : 8 WEEKS

MENTOR: NEELA SANTOSH KUMAR

discription of task 2 

This project is a fully functional real-time chat application developed using Node.js, Express.js, and Socket.IO, demonstrating how modern web applications enable seamless, instant communication between users. The primary objective was to implement a two-way, real-time messaging system over WebSockets, allowing multiple users to exchange messages instantly without the need for page reloads. This chat app features a clean and responsive user interface created with HTML, CSS, and JavaScript, and includes multiple advanced functionalities that enhance both user experience and technical robustness.

The application supports multiple users chatting in a common room and also includes support for private messaging (DMs), allowing one-on-one conversations securely. An emoji picker is integrated into the message input area, enabling users to send expressive, fun messages alongside text. It also features a dark/light theme toggle built purely with CSS and JavaScript, so users can personalize the appearance according to their preferences. The UI is designed to be minimal and mobile-responsive, ensuring usability across all device sizes.

From a backend perspective, the application uses Socket.IO to handle bidirectional communication between the server and all connected clients. Every time a user sends a message, it is instantly broadcast to all other users (or a specific user in the case of DMs), achieving true real-time functionality. In addition, the server is connected to a MongoDB database, which stores chat history so users can view past messages upon reconnecting or refreshing. This is managed with Mongoose, a Node.js library for MongoDB, ensuring data integrity and scalability.

A user authentication system is also implemented in a basic form to assign usernames to users upon login. Once logged in, users are directed to the chat interface where their username is retained for identification in conversations. This also makes it possible to filter and display messages user-wise, paving the way for private conversations and message history retrieval.

The entire project follows a modular code structure. The server.js file initializes the Express server, configures the Socket.IO logic, and handles MongoDB connection and message saving. The frontend is kept inside a public/ folder that contains index.html for the chat interface, style.css for design and theming, and script.js for handling socket events and DOM interactions. A separate views/ folder contains a login.html file for the user login system, ensuring a clear separation of concerns.

This application serves as a practical implementation of full-stack development principles. It demonstrates real-time client-server interaction, efficient use of web sockets, database integration for persistence, and interactive UI design. This project is ideal for learners and developers interested in real-world use cases of Socket.IO, Express.js, and MongoDB. Future enhancements may include message reactions, media/file sharing, notifications, and real-time typing indicators.
