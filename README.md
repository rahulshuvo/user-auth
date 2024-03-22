# MERN Authentication System

## Overview

This project is an Authentication system built using the MERN stack. It allows users to sign up, log in, and log out securely. The system utilizes JSON Web Tokens (JWT) for authentication and MongoDB for storing user data.

## Features

- User registration: Users can sign up by providing their email address and password.
- User authentication: Registered users can log in using their email and password.
- Password hashing: Passwords are hashed using bcrypt before being stored in the database for enhanced security.
- JSON Web Tokens (JWT): JWTs are generated upon successful login and used for subsequent authentication of protected routes.
- Protected routes: Certain routes are protected and can only be accessed by authenticated users.
- User logout: Users can log out, which invalidates their JWT.

## Technologies Used

- MongoDB: A NoSQL database used for storing user data.
- Express.js: A web application framework for Node.js used for building the server-side logic.
- React.js: A JavaScript library for building user interfaces used for the client-side development.
- Node.js: A JavaScript runtime used for building the server-side logic.
- bcrypt: A library used for password hashing.
- JSON Web Tokens (JWT): A compact, URL-safe means of representing claims to be transferred between two parties.

## Installation
Clone the repository:

```bash
git clone https://github.com/your_username/mern-authentication-system.git
```
Navigate to the project directory:
```bash
cd mern-authentication-system
```
Install server dependencies:
```bash
npm install
```
Navigate to the client directory:
```bash
cd client
```
Install client dependencies:
```bash
npm install
```
Go back to the project directory:
```bash
cd ..
```
Set up environment variables:
Create a .env file in the project root and add the following:
```bash
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```
Replace your_mongodb_uri with your MongoDB connection URI and your_jwt_secret with a secret key for JWT.

Run the development server:
```bash
npm run dev
```

## Usage
Once the development server is running, you can access the application at http://localhost:3000. From there, you can sign up, log in, and explore the authenticated features.


## Acknowledgments
- This project was inspired by various tutorials and resources available online.
- Special thanks to the creators and maintainers of the MERN stack.
