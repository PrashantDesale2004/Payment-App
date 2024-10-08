# Payment Web App

Payment Web App is a simple and secure payment application built using Node.js, Express, and MongoDB. The application allows users to check account balances and transfer money between accounts. It includes user authentication and ensures that transactions are processed securely using MongoDB's transaction support.

## Features

- **User Authentication**: Secure user login using middleware for protected routes.
- **Account Balance**: Users can check their current account balance.
- **Money Transfer**: Users can transfer money between accounts with balance checks and transaction integrity.
- **MongoDB Transactions**: Ensures that transfers between accounts are atomic and consistent.

## Technologies Used

- **Node.js**: JavaScript runtime environment.
- **Express**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing account and user information.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB.
- **JWT (JSON Web Tokens)**: For user authentication.
- **Bcrypt**: For password hashing.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PrashantDesale2004/Payment-App.git
   cd Payment-App
