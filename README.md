# E-Commerce-ORM


## Introduction

This is a simple Express.js API that uses Sequelize to connect to a MySQL database. The API has endpoints for creating, reading, updating, and deleting categories, products, and tags.


## Requirements

- Node.js >= 8.x
- MySQL >= 8.x
- Sequelize
- Express.js
- Dotenv


## Setup

1. Clone the repository: `git clone https://github.com/your-username/express-sequelize-mysql-api.git`
2. Install the dependencies: `npm install`
3. Create an environment variable file called `.env` and add the following variables:
```

DATABASE_NAME=your_database_name
MYSQL_USERNAME=your_mysql_username
MYSQL_PASSWORD=your_mysql_password

```

## Database Migration


To create the development database and seed it with test data, run the following commands:
```

npm migrate:latest
npm seed:run

```

## Starting the Server

To start the server, run the following command:

`npm start`


## Testing the API

You can use a tool like Insomnia Core to test the API.

To get a list of all categories, send a GET request to the `/categories` endpoint.

To create a new category, send a POST request to the `/categories` endpoint with the following JSON body:
```

JSON
{
  "name": "New Category"
}
```
To update a category, send a PUT request to the `/categories/:id` endpoint with the following JSON body:
```

JSON
{
  "name": "Updated Name"
}
```

To delete a category, send a DELETE request to the `/categories/:id` endpoint.


## Link to video demonstration

https://drive.google.com/file/d/156EYo00OxuzpmxYP80dqOd8K1xqgEssL/view  


## Conclusion

This is a simple example of how to build an Express.js API with Sequelize and MySQL. You can use this as a starting point to build your own custom APIs.