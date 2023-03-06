# Project Name: Ecommerce-Retial



## Description of the project

This is a retail e-commerce app for clothes and shoes, where users can browse and purchase products from various categories.

## Table of Contents**

**Technology User**

**Installation**

**Usage**

**Route**

**Tests**

**License**

## Technology Used

Javascript 
MySQL 
Node Js 

## Installation

To install the necessary dependencies, run the following command:

**npm install**

**This app requires the following dependencies**:

**dotenv** - to load environment variables from a .env file

**express** - to handle server and routing logic

**mysql2** - to connect to MySQL database

**sequelize** - to interact with the MySQL database using object-relational mapping


## Usage

To start the application, run the following command:

**npm start

This will start the server and make it available on http://localhost:3001.

## Routes

**Products**

GET /api/products - Returns a list of all products in the database.

GET /api/products/:id - Returns a single product with the specified ID.

POST /api/products - Adds a new product to the database.

PUT /api/products/:id - Updates a product with the specified ID.

DELETE /api/products/:id - Deletes a product with the specified ID.

**Categories**

GET /api/categories - Returns a list of all categories in the database.

GET /api/categories/:id - Returns a single category with the specified ID.

POST /api/categories - Adds a new category to the database.

PUT /api/categories/:id - Updates a category with the specified ID.

DELETE /api/categories/:id - Deletes a category with the specified ID.

**Tags**

GET /api/tags - Returns a list of all tags in the database.

GET /api/tags/:id - Returns a single tag with the specified ID.

POST /api/tags - Adds a new tag to the database.

PUT /api/tags/:id - Updates a tag with the specified ID.

DELETE /api/tags/:id - Deletes a tag with the specified ID.

## Tests

To run tests, run the following command:

**npm test


## License

This project is licensed under the MIT license.
