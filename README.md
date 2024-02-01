# ORM-Ecommerce-Back-End

## Table of Contents
 * [Description](#Description)
 * [Criteria](#Criteria)
 * [Video](#Video)
 * [Installation](#Installation)
 * [Usage](#Usage)
 * [License](#License)

## Description
Build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Video
Click the link below to view a walkthrough of the application

https://vimeo.com/908476371/ab0e12a45f?share=copy

## Installation
You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

## Usage
After running the installation commands and npm start or node server.js. Download Insomnia to test the application's GET routes to return all categories, all products, and all tags, return a single category, a single product, and a single tag, and show the application's POST, PUT, and DELETE routes for categories to successfully create, update, and delete data in my database.

## License
This project uses a MIT License
