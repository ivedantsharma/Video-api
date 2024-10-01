# Authentication System for API Access Tokens

## Overview
This project implements an authentication system for API access tokens with role-based permissions. The system allows users to register, log in, and manage access tokens based on their roles.

## Technologies Used
- **Node.js**: JavaScript runtime for server-side development
- **Express**: Web application framework for Node.js
- **MongoDB**: NoSQL database for storing user data
- **Mongoose**: ODM for MongoDB and Node.js
- **JWT (JSON Web Tokens)**: For secure token-based authentication
- **bcrypt**: For hashing passwords
- **dotenv**: For environment variable management
- **Cloudinary:** For storing the videos and images


## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ivedantsharma/Video-api.git
   cd video-api
2. **Install Dependencies:**
   ```bach
   npm install
3. **Configure Environment Variables: Create a .env file in the root directory and add your MongoDB URI and Cloudinary URI, Key and Password**
4. Run the Application:
   ```bash
   npm run dev

## Role-Based Permissions
Users can have different roles (e.g., admin, user) which define their permissions within the application.

## Contribution
Feel free to fork the repository and submit a pull request for any improvements or features.
