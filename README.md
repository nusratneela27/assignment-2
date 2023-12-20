# Mongoose Express CRUD Mastery Assignment

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
