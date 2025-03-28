## Book Search Engine
Welcome to the Book Search Engine! This project is designed to help avid readers like you search for new books, save them to your account, and keep track of your favorite reads. Whether you're looking for your next great book or simply want to organize your book collection, this app provides a seamless experience for discovering and saving books with ease.

Built using the MERN stack (MongoDB, Express, React, Node.js) and powered by GraphQL, the app offers a fast and responsive interface. With authentication through JWT, you can securely log in, manage your saved books, and customize your experience.

## Desciption
This is a Book Search Engine that allows users to search for books using the Google Books API, save books to their account, and manage a list of saved books. It has been refactored from a RESTful API to a GraphQL API using Apollo Server. The application is built using the MERN stack (MongoDB, Express.js, React, Node.js) with Apollo Server for handling GraphQL queries and mutations.

## Features
- Search for Books: Users can search for books using keywords.

- Save Books: Users can save their favorite books to their account.

- View Saved Books: Users can view and manage their saved books.

- User Authentication: Users can sign up, log in, and manage their account.

- GraphQL API: The app uses a GraphQL API with Apollo Server for fetching and modifying data.

- Technologies Used
MongoDB: Used for storing user data and saved books.

- Express.js: Backend web framework for handling routes.

- Node.js: JavaScript runtime environment for server-side code.

- React: Frontend framework for building the user interface.

- Apollo Server: GraphQL server for handling data queries and mutations.

- Apollo Client: Client-side library for interacting with the Apollo Server.

- JWT: JSON Web Tokens for handling authentication and user sessions.

- Download and install Node.js.

- MongoDB Atlas account or a local MongoDB instance to store data.

## Installation
Clone the repository to your local machine:

- bash
- Copy
- git clone repo
- cd repo
Install the dependencies:

- bash
- Copy
- npm install
- Set up your environment variables. Create a .env file in the root directory and add your MongoDB URI and JWT secret:

- ini
- Copy
- MONGODB_URI=your_mongodb_connection_string
- JWT_SECRET=your_jwt_secret
- Run the application:

- bash
- Copy
- npm run develop
- The application will now be running on http://localhost:3000. You can visit this URL to view the app in your browser.



License
This project is licensed under the MIT License - see the LICENSE file for details.