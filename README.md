# 📚 Book Search Engine

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![Apollo](https://img.shields.io/badge/Apollo%20GraphQL-311C87?style=flat&logo=apollo-graphql&logoColor=white)

A powerful MERN stack application that allows users to search for books via the Google Books API and save them to their profile. This application has been refactored from a RESTful API to a GraphQL API using Apollo Server.

![Book Search Engine Screenshot](https://raw.githubusercontent.com/treeewzrd/BOOK-SEARCH/main/client/src/assets/screenshot.png)

## 📋 Table of Contents

- [Description](#-description)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Deployment](#-deployment)
- [API Reference](#-api-reference)
- [License](#-license)
- [Contact](#-contact)

## 📝 Description

Book Search Engine is a full-stack web application that allows users to search for books using the Google Books API. Users can create accounts, log in, search for books, and save their favorite books to their profile. The application was built using the MERN stack (MongoDB, Express.js, React, Node.js) and has been refactored to use GraphQL with Apollo Server for more efficient data fetching.

## ✨ Features

- User authentication (signup, login, logout)
- Search for books using Google Books API
- Save books to your profile
- View all saved books
- Remove books from your saved list
- Responsive design for all devices

## 🛠️ Technologies Used

- **Frontend:**
  - React
  - Apollo Client
  - JWT for authentication
  - Bootstrap for styling

- **Backend:**
  - Node.js
  - Express.js
  - Apollo Server
  - GraphQL
  - MongoDB & Mongoose
  - JWT for authentication

## 🔧 Installation

1. Clone the repository: `git clone https://github.com/treeewzrd/BOOK-SEARCH.git`

2. Install dependencies: cd BOOK-SEARCH && npm install

3. Create a `.env` file in the server directory with your MongoDB connection string: MONGODB_URI='your_mongodb_connection_string' JWT_SECRET_KEY='your_jwt_secret'

4. Build the application: npm run build

## 🚀 Usage

1. Start the development server: npm run develop

2. Open your browser and navigate to `http://localhost:3000`

3. Create an account or log in

4. Search for books and save them to your profile

5. View your saved books by clicking on "See Your Books" in the navigation

## 🌐 Deployment

This application is deployed on Render with MongoDB Atlas. You can access the live application here:

[Book Search Engine on Render](https://book-search-engine.onrender.com)

### Deploying Your Own Version

To deploy this application to Render:

1. Create a MongoDB Atlas account and set up a cluster
2. Create a new Web Service on Render
3. Connect to your GitHub repository
4. Add the following environment variables:
   - `MONGODB_URI`: Your MongoDB Atlas connection string
   - `JWT_SECRET_KEY`: Your JWT secret key
5. Deploy your application

For detailed instructions, follow the [Deploy with Render and MongoDB Atlas](https://coding-boot-camp.github.io/full-stack/mongodb/deploy-with-render-and-mongodb-atlas) guide.

## 📖 API Reference

### GraphQL Queries

- `me`: Returns the logged-in user's data

### GraphQL Mutations

- [login(email, password)](cci:1://file:///c:/Users/kphil/OneDrive/Desktop/shit/MODULES/MODULE%2018/BOOK-SEARCH/client/src/utils/auth.ts:41:2-45:3): Authenticates a user and returns a token
- `addUser(username, email, password)`: Creates a new user and returns a token
- `saveBook(bookData)`: Saves a book to the user's account
- `removeBook(bookId)`: Removes a book from the user's saved books

## 📜 License

This project is licensed under the MIT License.

## 📞 Contact

**Timothy McGrath**  
Email: treewzrd@gmail.com  
GitHub: [treeewzrd](https://github.com/treeewzrd)

---

© 2025 Timothy McGrath. All Rights Reserved.