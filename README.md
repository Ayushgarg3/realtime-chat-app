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

## Files Created:

server.js - Complete backend with all API endpoints and Socket.IO handling
index.html - Full frontend client with beautiful UI
package.json - All required dependencies
README.md - Comprehensive setup and usage instructions

## Quick Setup:

1. Create project folder and add the files
2. Install dependencies:
         bash: npm install

3. Start MongoDB (locally or use MongoDB Atlas)
4. Run the application:
         bash: npm start

5. Open browser to http://localhost:3000

## Key Features Highlights:

Secure Authentication: Passwords are hashed, JWT tokens for sessions
Real-time Updates: Messages, online status, typing indicators all update instantly
Modern UI: Clean, responsive design with animations and hover effects
Error Handling: Comprehensive error handling and user feedback
Scalable Architecture: Clean separation of concerns, easily extensible
