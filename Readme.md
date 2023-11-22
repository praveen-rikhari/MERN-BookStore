# MERN Stack Book Store

## Overview

This is a simple book store application built using the MERN (MongoDB, Express.js, React, Node.js) stack. The main focus of this project is to demonstrate CRUD (Create, Read, Update, Delete) operations with books. The application allows users to add, edit, and delete books, storing the data in MongoDB Atlas(MongoDB cloud service).

## Technologies Used

- **MongoDB**: Database for storing book data.
- **Express.js**: Backend server framework.
- **React**: Frontend library for building user interfaces.
- **Node.js**: Runtime environment for server-side development.
- **React Router**: Handling navigation within the React app.
- **Hooks**: Utilized for state management in React components.
- **Tailwind CSS**: Used for basic styling of the application.
- **Vite**: Build tool for creating the React app.

## Features

- **Create Book**: Users can add a new book by providing its title, author name, and publish year.
- **Read Book**: View the list of books with their details.
- **Update Book**: Edit existing book information.
- **Delete Book**: Remove a book from the collection.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/mern-book-store.git
    cd mern-book-store
    ```

2. Install dependencies for both the server and client:

    ```bash
    # Install server dependencies
    cd server
    npm install

    # Install client dependencies
    cd ../client
    npm install
    ```

3. Configure MongoDB Atlas:

    - Create a MongoDB Atlas account and set up a cluster.
    - Replace the MongoDB connection string in `server/config/db.js` with your own.

4. Run the application:

    ```bash
    # Start the server (from the 'server' directory)
    npm start

    # Start the client (from the 'client' directory)
    npm run dev
    ```

5. Open your browser and navigate to `http://localhost:3000` to access the application.

## Contribution

If you'd like to contribute to this project, feel free to open issues or submit pull requests. Contributions are welcome!
