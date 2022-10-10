# E-Commerce Backend!
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  ## Description 
    AS A manager at an internet retail company
    I WANT a back end for my e-commerce website that uses the latest technologies
    SO THAT my company can compete with other e-commerce companies
  
  ## Table of contents
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [My Process](#my-process)
  - [Repository Link](#repository)
  - [Questions](#questions)
  
  ![ecommerce_gif1](./Assets/13-orm-homework-demo-01.gif)
  ![ecommerce_gif2](./Assets/13-orm-homework-demo-02.gif)
  ![ecommerce_gif3](./Assets/13-orm-homework-demo-03.gif)
  
  ## Installation
  This app was developed and tested using MySQL. Please refer to: [MySQL documentation](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/)
  
  You’ll need to use the MySQL2 and Sequelize packages to connect your Express.js API to a MySQL database and the dotenv package to use environment variables to store sensitive data, like your MySQL username, password, and database name.
  Use the schema.sql file in the db folder to create your database using MySQL shell commands. Use environment variables to store sensitive data, like your MySQL username, password, and database name.

    
    - Clone the repo
    - 'npm i'
    - source schema.sql to create database
    - 'npm run seed' to insert data into database
        
  ## Usage
    GIVEN a functional Express.js API
    WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
    THEN I am able to connect to a database using Sequelize
    WHEN I enter schema and seed commands
    THEN a development database is created and is seeded with test data
    WHEN I enter the command to invoke the application
    THEN my server is started and the Sequelize models are synced to the MySQL database
    WHEN I open API GET routes in Insomnia Core for categories, products, or tags
    THEN the data for each of these routes is displayed in a formatted JSON
    WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
    THEN I am able to successfully create, update, and delete data in my database
      
  ## License
  MIT License: https://choosealicense.com/licenses/mit/
  ## My Process
  ### Built With
  - MySQL
  - Javascript
  - Sequelize
  - Express


Database Models <br>
Four databse models were created to to mimic a E-commerce backend.

Associations <br>
Using Sequelize, association methods were used to build relationships between the models: <br>
Product belongs to Category, as a category can have multiple products but a product can only belong to one category.<br>
Category has many Product models.<br>
Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.<br>
Tag belongs to many Product models.<br>

API Routes were then created to Perform RESTful CRUD Operations.
  
  ## Repository
  - [Video Walkthrough](https://drive.google.com/file/d/122zHg4QFvXtQEl6dXzm9hU3PaxpY2JvL/view?usp=sharing)
  - [Project Repo](https://github.com/dnsnguy08/e_commerce_back_end)
  ## Questions
  For any questions, please reach out to:
  - Dennis Nguyen
  - [GitHub Profile](https://github.com/dnsnguy08)
