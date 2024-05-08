# Jottr - A Blogging Web Application

Jottr is a full-stack web application for creating and managing blogs. It allows users to sign up, create, edit, and delete their own blog posts. Jottr is built using React for the frontend, Node.js and Express.js for the backend, and MongoDB for the database.

## Features
- User authentication: Users can sign up and log in to create and manage their blog posts.
- Create and edit posts: Users can create new blog posts and edit existing ones.
- Delete posts: Users can delete their own blog posts.
- Responsive design: The application is optimized for various screen sizes.

## Setup

To run Jottr locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/jottr.git
2. Navigate to the project directory:
    ```bash
   cd jottr
3. Install dependencies for both the frontend and backend:
   ```bash
    cd client
    npm install
    cd ../server
    npm install
4. Set up the environment variables:
   Create a .env file in the server directory.
   Add the following variables
     PORT=5000
     MONGODB_URI=<your_mongodb_connection_string>
     SECRET_KEY=<your_secret_key_for_jwt>

5. Start the backend server:
   ```bash
   npm start
6. Start the frontend development server:
   ```bash
   cd ../client
   npm start
7. Open your browser and visit http://localhost:3000 to access Jottr.
   

   
   
