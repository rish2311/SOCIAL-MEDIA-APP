# SOCIAL MEDIA APP

Welcome to the SOCIAL MEDIA APP! This project is a full-stack application built using the MERN stack (MongoDB, Express, React, Node.js) designed to facilitate social interactions among users. It allows users to create posts, follow other users, and comment on posts, providing a platform for sharing thoughts and experiences.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- **User Authentication**: Secure user registration and login using JWT.
- **Profile Management**: Users can create and manage their profiles.
- **Post Creation**: Users can create, edit, and delete posts.
- **Comments**: Users can comment on posts and interact with other users.
- **Follow System**: Users can follow and unfollow each other.
- **Responsive Design**: Optimized for both mobile and desktop views.

## Technologies Used
- **MongoDB**: NoSQL database for storing user and post data.
- **Express**: Web framework for Node.js, used to build the server.
- **React**: Frontend library for building user interfaces.
- **Node.js**: JavaScript runtime for building the server-side application.
- **Mongoose**: ODM for MongoDB, providing a schema-based solution to model application data.
- **JWT**: JSON Web Tokens for secure user authentication.

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (version >= 14)
- MongoDB (or use a cloud MongoDB service)

### Clone the Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/rish2311/SOCIAL-MEDIA-APP.git
   cd SOCIAL-MEDIA-APP

#Backend Setup:
Navigate to the server directory-

cd backend
Install the required packages:

npm install
Create a .env file in the backend directory and add your MongoDB connection string:

MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key

Start the backend server:
npm start

Frontend Setup
Navigate to the client directory:
cd ../frontend

Install the required packages:
npm install

Start the frontend application:
npm start

Open your web browser and navigate to http://localhost:3000 to access the application.

#Usage
- Register a new account or log in if you already have an account.
- Create posts and interact with others by commenting and following users.
- Explore the features of the app and enjoy the social media experience!

Contributing:
Contributions are welcomed! If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create your feature branch:
git checkout -b feature/MyFeature

Commit your changes:
git commit -m "Add some feature"

Push to the branch:
git push origin feature/MyFeature

Open a pull request.
