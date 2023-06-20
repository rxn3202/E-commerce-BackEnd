# E-commerce Back End

## Description

This is a back-end application for an E-commerce site, which allows for full CRUD operations on the data within the database. The application was built using Node.js and Express.js to setup the API endpoints, Sequelize as the ORM to interact with a MySQL database, and dotenv for environment variable handling.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Mock Up](#mock-up)
- [Technology Used](#technology-used)

## Installation

- Make a copy of this repository on your personal computer.
- Go to the project folder.
- Execute npm install to install the necessary dependencies.
- Configure your MySQL database and modify the connection details in the connection.js and .env file
- Start the application by running npm start.

## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

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

## Mock up
[Click on the link for the Video Demonstration](https://drive.google.com/file/d/1EXzMvmgyaFNzsBAWb3l-1My6knzUHd5G/view)

## Technologies Used

- Express.js
- Javascript
- Node js
- Mysql2
- Sequelize