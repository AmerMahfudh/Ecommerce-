#To install open terminal go to the folder then
## `npm install`

###open .env file and put your value for the env variable.


#To run type on terminal and press enter
## `npm run start:dev`


# E-commerce Application

## Project Description
The `E-commerce Application` is a comprehensive system for managing an online store, built using the NestJS framework. The project includes multiple services for managing users, products, orders, and reviews, as well as setting up and configuring the database connection.

## Key Features

### Users Management Service
- **Sign Up and Sign In**: Register new users and validate their credentials during sign-in using bcrypt encryption and JWT token issuance.
- **Retrieve Users**: Retrieve details of all users or a specific user.
- **User Management**: Update and delete user accounts.

### Products Management Service
- **Create and Update Products**: Add and update product details, including associated categories.
- **Search and Filter**: Search for products and filter results based on category, price, ratings, and more.
- **Stock Management**: Update stock levels based on order statuses.

### Orders Management Service
- **Create Orders**: Create orders and link them to users and products.
- **Retrieve Orders**: Retrieve details of all orders, including shipping details, users, and associated products.
- **Update Order Status**: Update the status of orders and manage inventory accordingly.
- **Cancel Orders**: Cancel orders and update inventory.

### Reviews Management Service
- **Create and Update Reviews**: Add and update product reviews by users.
- **Retrieve Reviews**: Retrieve all reviews or reviews associated with a specific product.
- **Review Management**: Delete unwanted reviews.

### Database Configuration Service
- **Initialize Database Connection**: Setup database connection for PostgreSQL using TypeORM and dotenv.
- **Manage Migrations**: Configure paths for entities and migrations.

### Current User Middleware
- **Set Current User**: Set the current user to the `Request` object for easy access during the request lifecycle.

## Technologies and Tools Used
- **NestJS**: A Node.js framework for building server-side applications.
- **TypeORM**: ORM library for interacting with the database.
- **PostgreSQL**: Database used for storing data.
- **bcrypt**: Library for password hashing and validation.
- **jsonwebtoken**: Library for issuing and managing tokens.
- **dotenv**: Library for managing environment variables.

## Getting Started with the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository


