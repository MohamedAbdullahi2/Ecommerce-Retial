# Project Name: Ecommerce-Retial



## Description of the project

This is a retail e-commerce app for clothes and shoes, where users can browse and purchase products from various categories.

**Table of Contents

**Installation

**Usage

**Routes

**Tests

**License



# Installation

To install the necessary dependencies, run the following command:

**pm install

**This app requires the following dependencies:

**dotenv** - to load environment variables from a .env file
**express** - to handle server and routing logic
**mysql2** - to connect to MySQL database
**sequelize** - to interact with the MySQL database using object-relational mapping


**Usage

To start the application, run the following command:

**npm start

This will start the server and make it available on http://localhost:3001.

**Routes

GET /api/products - get all products
GET /api/products/:id - get a single product by id
POST /api/products - create a new product
PUT /api/products/:id - update a product by id
DELETE /api/products/:id - delete a product by id
GET /api/categories - get all categories
GET /api/categories/:id - get a single category by id
POST /api/categories - create a new category
PUT /api/categories/:id - update a category by id
DELETE /api/categories/:id - delete a category by id
GET /api/tags - get all tags
GET /api/tags/:id - get a single tag by id
POST /api/tags - create a new tag
PUT /api/tags/:id - update a tag by id
DELETE /api/tags/:id - delete a tag by id


## Tests

To run tests, run the following command:

**npm test


**License

This project is licensed under the MIT license.
