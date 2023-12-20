# Mongoose Express CRUD Mastery Assignment

## Project Summary

## Node.js Express Application with TypeScript, MongoDB, and Mongoose

This Node.js Express application is built with TypeScript and leverages MongoDB with Mongoose for robust user data and order management. The implementation integrates bcrypt for secure password hashing and Zod for thorough input validation. The application features a set of eight routes, enabling the creation, retrieval, updating, and deletion of user records, along with seamless management of user orders.

## Local Setup Instructions

1. Clone the repository:
   ```bash
   git clone
   ```
2. Navigate to the project directory:
   ```bash
   cd /your-folder
   ```
3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root of the project and set the following environment variables:

   ```env
   PORT=5000
   DB_URL=your_mongodb_url
   BCRYPT=12
   ```

   Replace `your_mongodb_url` with the actual MongoDB URL.

## API Endpoints

### Create a new user

- **POST /api/users**:
  - Description: Create a new user.

### Get users

- **GET /api/users**:
  - Description: Get all users.

### Get a single user

- **GET /api/users/:userId**:
  - Description: Get a single user by ID.

### Update a user

- **PUT /api/users/:userId**:
  - Description: Update a user by ID.

### Delete a user

- **DELETE /api/users/:userId**:
  - Description: Delete a user by ID.

### Add a product to user's orders

- **PUT /api/users/:userId/orders**:
  - Description: Add a new product to a user's orders.

### Get all orders for a user

- **GET /api/users/:userId/orders**:
  - Description: Get all orders for a user.

### Get total price of all orders for a user

- **GET /api/users/:userId/orders/total-price**:
  - Description: Get the total price of all orders for a user.
