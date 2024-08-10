# ChatApp-MERN-Stack

## Description

ChatApp is a real-time chat application built using the MERN stack with Socket.IO for real-time communication. The application allows users to create accounts, log in, and engage in one-on-one or group chats. The user interface is styled using Tailwind CSS to provide a modern and responsive design.

## Technologies Used

### Core Technologies

- **MongoDB**: NoSQL database for storing user data and chat history.
- **Express.js**: Web application framework for Node.js, used for building the server.
- **React.js**: Frontend library for building the user interface.
- **Tailwind CSS**: Utility-first CSS framework for styling the application.
- **Node.js**: JavaScript runtime for building the server-side of the application.

### Other Technologies

- **Socket.IO**: Library for real-time, bidirectional communication between clients and the server.
- **JWT (JSON Web Token)**: For secure authentication and authorization.

## Set up environment variables

    Create a `.env` file in the `server` directory and add the following environment variables:

    ```env
    MONGODB_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

## Features

- User registration and authentication using JWT.
- Real-time messaging using Socket.IO.
- Responsive and modern UI with Tailwind CSS.
- One-on-one and group chat functionality.

---

Enjoy chatting!
