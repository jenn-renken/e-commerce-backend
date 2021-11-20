# e-commerce-backend

## Video Demo
https://watch.screencastify.com/v/Nq1aoohuUkWNmNaaKenQ

## Description
This is the functional backend for an e-commerce website.

## Technologies
- mysql
- express.js
- sequelize
- .env

## Usage
- download code 
- run NPM install
- add .env file to root directly with the following information:
    DB_NAME='ecommerce_db'
    DB_USER='root'
    DB_PW='xxx'
- start mysql and run source schema.sql
- run npm seed
- run npm start
- view routes in Insomia Core

## Acceptance Criteria
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database 

