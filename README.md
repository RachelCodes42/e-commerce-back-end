
# E-Commerce Website Backend

## Description
This repository contains the back end codebase for an e-commerce website developed for an internet retail company. The primary goal of this project is to provide a robust and efficient backend system using the latest technologies to enable the company to compete effectively with other e-commerce businesses. It includes the implementation of a RESTful API using Express.js, Sequelize for database management, and support for various CRUD operations.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation
<!-- Add installation instructions here -->
Prerequisites:
1. Node.js and npm installed on your machine.
2. MySQL server installed and running.
3. Insomnia Core (or any API testing tool) for testing the API endpoints.

Installation:
1. Clone the repository: git clone https://github.com/RachelCodes42/e-commerce-back-end.git
2. Change to the project directory: cd ecommerce-backend
3. Install dependencies: npm install

## Usage
<!-- Add usage information here -->
Database Configuration:
1. Create an environment variable file (.env) in the root directory of the project.
2. Add the following database configuration information to the .env file:
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=3306

Running the Application:
1. To create and seed the development database, run: npm run seed
2. To start the server and sync Sequelize models with the MySQL database, run: npm start

API Routes:
- GET /api/categories - Get all categories.
- GET /api/products - Get all products.
- GET /api/tags - Get all tags.

- POST /api/categories - Create a new category.
- POST /api/products - Create a new product.
- POST /api/tags - Create a new tag.

- PUT /api/categories/:id - Update a category by ID.
- PUT /api/products/:id - Update a product by ID.
- PUT /api/tags/:id - Update a tag by ID.

- DELETE /api/categories/:id - Delete a category by ID.
- DELETE /api/products/:id - Delete a product by ID.
- DELETE /api/tags/:id - Delete a tag by ID.

## License
<!-- Add license badge and explanation here -->
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)(http://opensource.org/licenses/MIT)

## Contributing
<!-- Add contribution guidelines here -->
- Node.js 
- Express.js
- Sequelize
- ORM
- MySQL
- Database
- Insomnia Core (for API testing)

## Tests
<!-- Add test instructions here -->
- Insomnia Core for testing the API endpoints.

## Questions
GitHub: [Your GitHub Profile](https://github.com/RachelCodes42)
Email: hochman.rachel@gmail.com
  