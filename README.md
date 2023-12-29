# E-commerce Backend 
## Table of Contents
[Description](#description)
[Installation](#installation)
[Usage](#usage)
[License](#license)
[Contribution-Guidelines](#guidelines)
[Video/Images](#video)
[Test](#test)
[Questions](#questions)
## Description
This is the back-end component of an E-Commerce application. It provides API endpoints for managing categories, products, and tags in an online store. The application is built using Node.js, Express.js, Sequelize (an ORM), and MySQL as the database.
## Installation
To use the E-Commerce Back-End, follow these steps:

Clone this repository to your local machine.

Install the required dependencies:
run "npm install"

Login to your mysql using the command line/bash.
run "mysql -u [username] -p;"

Set up your database by creating a .env file in the project root directory. Add your sequelize database configuration as follows:

DB_NAME='ecommerce_db'
DB_USER='your-database-username'
DB_PASSWORD='your-database-password'

Create the necessary database schema using the provided SQL files in the "db" directory.
In bash, once you logged into mysql: CREATE DATABASE ecommerce_db;

Seed your database with data.
run "node seeds/index.js"

Start the application.
run "node server.js"
## Usage
Technologies used were Node.js, Express.js, Sequelize (an ORM), and MySQL as the database and JavaScript.
## License
[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
This application is covered by the Open license. 
## Contribution-Guidelines
Open an issue from the issues tab at the repository homepage to report problems.
## Video/Images

## Questions
GitHub: https://github.com/Stephen-Garcia