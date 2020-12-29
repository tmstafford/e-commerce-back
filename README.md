# E-commerce Back End 

## Description

This is the back-end for an e-commerce site built to connect a working Express.js API to a MySQL database. The application uses Sequelize to interact with the MySQL database. Once the database is connected and the server is started, users can test all routes through Insomnia to create, read, update, and delete data in the database. The GET routes return all categories, all products, and all tags stored in the database, and can also be used to GET a single category, a single tag, and a single product by ID. The POST routes can be tested to add a category, product, or tag to the database and the PUT routes can be tested to update any category, product, and tag by their respective ID. The DELETE route can be tested to delete any category, product, or tag from the database by ID. 

Watch the Full [Walkthrough Video Here](https://drive.google.com/file/d/1WI6MU1wHroMj2jjBfC6HSyGig17joq-G/view).


## Installation

Clone this repository, then initialize the node package manager in the root of the project folder. Then from the command line, run

    npm install mysql2 
    npm install sequelize 
    npm install dotenv
    npm install express
    
To install all dependencies needed for this application.

## Usage

To use the application, be sure to have MySQL installed. Then from the root of your project folder, run the MySQL shell command 
      
      mysql -u root -p
 And enter your secure password. Then from the command line, run `source db/schema.sql`. Exit the SQL shell and in the root of the folder from the command line, run `npm run seed` to seed the database, and `npm start` to connect to the server. Head to Insomnia Core to test all API routes and create, read, update, and delete data from the database. 


