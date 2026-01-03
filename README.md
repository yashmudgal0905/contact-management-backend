# Contact Management App – Backend

This is the backend API for a Contact Management application built using Node.js, Express.js, and MongoDB.

## Features
- REST APIs to create and fetch contacts
- MongoDB Atlas for database storage
- Express.js for backend routing
- Environment variable configuration using dotenv

## API Endpoints
- GET /api/contacts – Fetch all contacts
- POST /api/contacts – Add a new contact

## Tech Stack
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose

## Setup Instructions
1. Clone the repository
2. Navigate to the server folder
3. Install dependencies:
   npm install
4. Create a .env file and add:
   MONGO_URI=your_mongodb_connection_string
5. Start the server:
   npx nodemon index.js

## Deployment
The backend is deployed using Render.

## Author
Yash Mudgal
