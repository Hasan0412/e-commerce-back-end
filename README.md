# E-Commerce Back End (Object-Relational Mapping)

## Description

- A Node.js application built with Express.js.
- Uses Sequelize ORM to interact with a MySQL database.
- Features routes for managing product categories, products, and tags.
- Supports CRUD (Create, Read, Update, Delete) operations for categories, products, and tags.
- Implements database seeding for initial data setup.
- Utilises environment variables stored in a .env file for configuration.
- Provides API endpoints for retrieving and manipulating e-commerce data.
- Demonstrates database synchronisation and server initialisation.

## How to Use

1. Clone the repository
2. Install dependencies with 'npm i'.
3. Type 'mysql -u root -p' in the integrated terminal, then type your password for mysql.
4. Once on mysql, type 'source db/schema.sql' and then type 'quit', to leave mysql.
5. Then run 'npm run seed', followed by 'npm run start', to start the server.
6. Once the server is running, go to Postman/Insomnia, to complete CRUD operations.

## Screenshots

#### GET Request:

![screenshot](/Screenshots/get.png)

#### POST Request:

![screenshot](/Screenshots/post.png)

#### PUT Request:

![screenshot](/Screenshots/put.png)

#### DELETE Request:

![screenshot](/Screenshots/delete.png)

## Links

[Walkthrough](https://drive.google.com/file/d/1DYEW4sz3WA1gwNy1Z2nHte-5EZsjLxzI/view?usp=drive_link)

[Starter Code](https://github.com/coding-boot-camp/fantastic-umbrella)