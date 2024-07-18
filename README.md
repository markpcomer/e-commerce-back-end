# 13 Object-Relational Mapping (ORM): E-Commerce Back End
![License](https://img.shields.io/badge/License-MIT%20-blue.svg)


## Overview

This project focuses on developing the back end of an e-commerce platform by setting up a functional Express.js API that utilizes Sequelize to interact with a MySQL database. The application enables users to manage categories, products, and tags, supporting CRUD operations through API endpoints.

## Getting Started

To begin with this project, please follow these steps:

1. Clone the repository to your local system.
2. Set up your MySQL database and configure the necessary environment variables.
3. Install the required dependencies by running `npm install`.
4. Create and seed the database using `npm run seed`.
5. Start the server with `npm start`.


## Usage

To use the application, follow these instructions:

1. Configure environment variables by creating a `.env` file in the root directory. Include the following variables:
   - `DB_NAME`: Your MySQL database name.
   - `DB_USER`: Your MySQL username.
   - `DB_PASSWORD`: Your MySQL password.
2. Set up your MySQL database using the `schema.sql` file found in the `db` folder.
3. Seed the database with sample data by running: `npm run seed`
4. Launch the server using: `node server.js`
5. Test the API endpoints using Insomnia.

For further testing API endpoints instruction, watch this demo video:
[VIEW DEMO HERE](https://www.loom.com/share/42177a00e2ea4068aa9a809bbebfa88d?sid=49fb1018-f2e4-488b-8947-a80c1bf3e0f7)


## Technologies Used

- JavaScript
- Node.js
- Express.js
- Sequelize
- MySQL
- Insomnia
- dotenv
- npm

## License

This project is licensed under the MIT License. 









