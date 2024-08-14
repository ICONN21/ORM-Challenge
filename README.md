# E-Commerce Back End

## Description

This project involves building the back end for an e-commerce site using Node.js, Express.js, Sequelize, and PostgreSQL. The goal is to create a functional Express API that interacts with a PostgreSQL database using Sequelize as the ORM (Object-Relational Mapping). This project demonstrates how a modern e-commerce platform operates on the back end, handling product, category, and tag management.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Routes](#routes)
- [Walkthrough Video](#walkthrough-video)
- [License](#license)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ecommerce-backend.git
   cd ecommerce-backend

2. Install dependencied:
    npm install
3. Set up environment by creating a .env file adding the following: 
        DB_NAME=ecommerce_db
        DB_USER=your_postgres_username
        DB_PASSWORD=your_postgres_password

4. CREATE DATABASE ecommerce_db;

5. Seed database: npm run seed

6. Start server: npm start


## Usage 
This application provides a RESTful API to manage an e-commerce platform's backend. You can perform CRUD operations on Products, Categories, and Tags. Use an API client like Insomnia or Postman to interact with the API.

## User Story
AS a manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria 
GIVEN a functional Express.js API
WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the PostgreSQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Routes
Category Rotues
- **GET** `/api/categories` - Get all categories
- **GET** `/api/categories/:id` - Get a single category by ID
- **POST** `/api/categories` - Create a new category
- **PUT** `/api/categories/:id` - Update a category by ID
- **DELETE** `/api/categories/:id` - Delete a category by ID

Product Routes
- **GET** `/api/products` - Get all products
- **GET** `/api/products/:id` - Get a single product by ID
- **POST** `/api/products` - Create a new product
- **PUT** `/api/products/:id` - Update a product by ID
- **DELETE** `/api/products/:id` - Delete a product by ID

Tag Routes
- **GET** `/api/tags` - Get all tags
- **GET** `/api/tags/:id` - Get a single tag by ID
- **POST** `/api/tags` - Create a new tag
- **PUT** `/api/tags/:id` - Update a tag by ID
- **DELETE** `/api/tags/:id` - Delete a tag by ID

## Walkthrough Video 
- Creating the schema in PostgreSQL
- Seeding the database
- Starting the server
- Testing all the routes in Insomnia

[Walkthrough Video](https://drive.google.com/file/d/1t6VRXATfOYKeEij7rJ3abYGcbJvS2FXp/view) (Link your video here)


## License
© 2024 [Your Name or Company]. All Rights Reserved.




