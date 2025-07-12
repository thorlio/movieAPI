# Movie API (Backend)

This is the backend for the **myFlix** app, a movie database that allows users to browse movies, register, and manage their profiles. The backend is built using **Node.js, Express, MongoDB, and Mongoose** with **JWT authentication** via **Passport.js**.

## Features

- User authentication with JWT
- CRUD operations for users and movies
- Secure password hashing with bcrypt
- Mongoose for database management
- RESTful API design
- Passport.js for authentication
- Middleware for security and validation

## Technologies Used

- Node.js - JavaScript runtime
- Express.js - Web framework
- MongoDB - NoSQL database
- Mongoose - Object data modeling
- Passport.js - Authentication middleware
- JWT (JSON Web Tokens) - Secure authentication method
- bcrypt.js - Password hashing
- Morgan - HTTP request logger
- CORS - Cross-Origin Resource Sharing

## File Structure

```
movieapi/
├── node_modules/
├── out/               # JSDoc generated documentation
├── public/            # Static public files (e.g., index.html)
├── .env               # Environment variables (not committed)
├── .gitignore
├── auth.js            # Passport JWT setup
├── index.js           # Main entry point for Express app
├── index.html         # Default HTML served (optional for testing)
├── models.js          # Mongoose schemas
├── passport.js        # JWT strategy config
├── package.json
├── package-lock.json
└── README.md
```
