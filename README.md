# e-commerce-ORM

## Table of Contents

 1. [Description](#description)
 2. [Installation and Use](#installation-and-use)
 3. [User Story](#user-story)
 4. [Acceptance Criteria](#acceptance-criteria)
 5. [Video Link](#video-link)

## Description

Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.
## Installation and Use

Clone or Fork this Repo to your local device. From the Root Directory, Git Bash npm i to download all required dependencies, then initiate the DB with 'mysql -u root -p'. Once complete type 'source db/schema.sql' to create the table(s) then exit the sql command line and type 'npm run seed'. This will seed the data to your table(s). After that, 'npm start' should start the server. 
## User Story

``AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies``
## Acceptance Criteria

* GIVEN a functional Express.js API
* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
* THEN I am able to connect to a database using Sequelize
* WHEN I enter schema and seed commands
* THEN a development database is created and is seeded with test data
* WHEN I enter the command to invoke the application
* THEN my server is started and the Sequelize models are synced to the MySQL database
* WHEN I open API GET routes in Insomnia for categories, products, or tags
* THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia
* THEN I am able to successfully create, update, and delete data in my database

## Video Link


