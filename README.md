# Cart-Engine

## Description

Cart-Engine is a back end for an e-commerce website built using the latest technologies. It provides a functional Express.js API integrated with Sequelize to interact with a PostgreSQL database. With Cart-Engine, internet retail businesses can compete effectively in the dynamic e-commerce market. 

## Features

- Express.js API: Utilizes Express.js to handle HTTP requests and responses, providing a robust API structure.

- CRUD Operations: Supports Create, Read, Update, and Delete operations for categories, products, and tags through RESTful API routes.

- Data Validation: Validates data input to ensure integrity and consistency within the database.

- Associations: Establishes relationships between models, such as products belonging to categories and having multiple tags.

- Environment Variables: Safely stores sensitive data like database credentials using environment variables.

- Automatic Database Sync: Syncs Sequelize models with the PostgreSQL database automatically on server start-up.

## Usage

1. Setup Environment Variables: Create a .env file and add your PostgreSQL username, password, and database name.
2. Database Initialization: Execute the schema.sql file in the db folder to create the necessary database structure.
3. Install Dependencies: Run `npm i` to install project dependencies.
4. Seed Database: Use `npm run seed` to seed the database with test data.
5. Start Server: Launch the server by running `npm start`.
6. Test API Routes: Utilize tools like Insomnia to test the implemented API routes for categories, products, and tags.
7. Perform CRUD Operations: Test Create, Read, Update, and Delete operations for categories, products, and tags using the provided API routes.

## Walkthrough Video

[Link to walkthrough Video](https://drive.google.com/file/d/1kmPFLCO-mkhmUyY_HE16h-Hbiic4FH8-/preview)

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](/Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](/Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](/Assets/13-orm-homework-demo-03.gif)

## License

[![License: None](https://img.shields.io/badge/License-None-lightgrey.svg)](#)