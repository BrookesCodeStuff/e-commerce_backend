# E-commerce Back End

## Description

E-commerce is an ever-growing sector of the tech industry. This purpose of this project is to solidify my understanding of the fundamental backend architecture of e-commerce sites using relational database structures. I have built both the relational database tables to store data and APIs to fetch and return that data so that it could be used in a front end e-commerce website.

## Usage

This application allows users to manage an inventory of products, their associated categories, and tags. API routes will allow a user to fetch and update data through their front end, and display it on their webpage (not included).

## Installation

The application requires NodeJS and MySQL. It's built using Express.js as the middleware and Sequelize for managing the SQL queries. To install, download (and unzip) or clone this repository, then browse to the application directory and run `npm install`. Once all of the dependencies have been downloaded and installed, the connect to your MySQL instance and run `source db/schema.sql` to create and use the database. You can then exit MySQL.

To seed the database with "starter" categories, products, and tags - if desired - after the database has been created and MySQL has been closed, change line 13 of the server.js file from `sequelize.sync({ force: false })` to `sequelize.sync({ force: true })`. Then, in the command line, run the command `npm run seed`. Then, please change the `force` property back to `false` on line 13 of the server.js file.

Once those steps have been completed, start the program by running `npm start` from the command line. You can then use an API platform such as Postman or Insomnia to make API calls.

## Walkthrough Video

[Walkthrough Demonstration](https://drive.google.com/file/d/11pVQy6b97BemqmjAOYwzud6_eLSnqnmR/view)
