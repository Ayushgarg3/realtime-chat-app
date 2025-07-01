# Real-Time Chat Application

A full-featured real-time chat application built with Node.js, Express, Socket.IO, and MongoDB.

## Features

- **User Registration & Authentication**: Secure user registration and login with JWT tokens
- **Real-time Messaging**: Instant message delivery using Socket.IO
- **Online/Offline Status**: See who's currently online and their last seen status
- **Message Timestamps**: All messages include precise timestamps
- **Typing Indicators**: See when other users are typing
- **Responsive Design**: Works on desktop and mobile devices
- **Secure Password Storage**: Passwords are hashed using bcryptjs

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Real-time Communication**: Socket.IO
- **Authentication**: JWT (JSON Web Tokens)
- **Security**: bcryptjs for password hashing
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)

## Prerequisites

Before running this application, make sure you have:

- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas)
- npm or yarn package manager

## Installation

1. **Clone or create the project files**:
   ```bash
   mkdir chat-app
   cd chat-app
   ```

2. **Create the following files**:
   - `server.js` (backend server code)
   - `package.json` (dependencies)
   - Create a `public` folder and add `index.html`