# Social Media Web App (MERN Stack)

A simple social media web application built using the MERN stack (MongoDB, Express.js, React, Node.js) that allows users to create accounts, post content, like and comment on posts, and connect with others.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Run the Application](#run-the-application)
- [Contributing](#contributing)
  
## Overview

This is a social media platform where users can interact with each other by creating posts, liking, and commenting on posts. It's built on the MERN stack, making it a modern, full-stack JavaScript application.

## Features

- User authentication (signup/login)
- User profile creation
- Create, edit, and delete posts
- Like and comment on posts
- Follow/unfollow other users
- Responsive UI

## Technologies Used

- **MongoDB**: A NoSQL database to store user data and posts.
- **Express.js**: A web framework for Node.js to build APIs.
- **React**: A JavaScript library for building the frontend of the application.
- **Node.js**: A runtime environment to run JavaScript server-side.
- **JWT (JSON Web Tokens)**: For user authentication and secure login sessions.
- **Bcrypt.js**: For password hashing.

## Getting Started

To get a local copy of this project running, follow the instructions below:

### Prerequisites

Ensure that you have the following software installed:

- Node.js (v12 or later)
- MongoDB (you can use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) if you prefer cloud storage)
- npm (Node Package Manager)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vikaskumarrr9/Social-Media-WebApp.git
   cd social-media-web-app
   ```

2. **Install Backend dependencies**:
   Go to the backend directory and install dependencies:
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend dependencies**:
   Go to the frontend directory and install dependencies:
   ```bash
   cd frontend
   npm install
   ```

### Run the Application

1. **Set up environment variables**:
   You will need to set up the following environment variables for both the backend and frontend:
   - `MONGO_URI` (MongoDB URI connection string)
   - `JWT_SECRET` (A secret key for JWT)
   - `PORT` (The port your backend will run on)

2. **Run the backend**:
   Navigate to the backend folder and run the server:
   ```bash
   cd backend
   npm start
   ```

   The backend will now be running on the specified port (e.g., `http://localhost:5000`).

3. **Run the frontend**:
   Navigate to the frontend folder and run the client:
   ```bash
   cd frontend
   npm start
   ```

   The frontend will now be available on `http://localhost:3000`.

### Testing the Application

After completing the setup, you can test the app by:

1. Signing up and logging in as a user.
2. Creating posts, liking them, and commenting.
3. Checking the profile page and following/unfollowing other users.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request with your changes. Make sure to follow the coding standards and write tests for your features when possible.
