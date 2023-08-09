# Express.js API with Sequelize

This repository contains a functional Express.js API built using Sequelize, a powerful Node.js ORM, to interact with a MySQL database. The API provides endpoints for managing categories, products, and tags for an ecommerce application. It follows a RESTful architecture and includes CRUD (Create, Read, Update, Delete) operations for each model.

## Installation
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/express-sequelize-api.git
cd express-sequelize-api
Install dependencies:

sh

npm install
Create a .env file based on the .env.EXAMPLE template and provide your MySQL database credentials:

sh

DB_NAME=your_db_name
DB_USER=your_db_user
DB_PW=your_db_password

## Usage
Starting the Server
To start the Express.js server, run:

sh

npm start
The server will be running at http://localhost:3001 or the specified port.

## Testing Endpoints
Use tools like Insomnia Core or Postman to test the API endpoints. Available routes include:

/api/categories (GET, POST, PUT, DELETE)
/api/products (GET, POST, PUT, DELETE)
/api/tags (GET, POST, PUT, DELETE)

## API Routes
The API provides the following routes:

Categories

GET /api/categories
GET /api/categories/:id
POST /api/categories
PUT /api/categories/:id
DELETE /api/categories/:id
Products

GET /api/products
GET /api/products/:id
POST /api/products
PUT /api/products/:id
DELETE /api/products/:id
Tags

GET /api/tags
GET /api/tags/:id
POST /api/tags
PUT /api/tags/:id
DELETE /api/tags/:id

## Database
The application uses Sequelize to interact with a MySQL database. Database schema and seed data can be initialized using the provided SQL schema file (schema.sql) and seed scripts.

To seed the database with test data, run:

sh
npm run seed

## Contributing
Contributions are welcome! If you find any issues or have improvements to suggest, feel free to open a pull request.

## License
This project is licensed under the MIT License.

