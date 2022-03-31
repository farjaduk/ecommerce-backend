# E-commerce Back End 

## Description:

The program allows for full CRUD functionality of a databse containing 3 tables, categories, products and tags, in the backend.


# Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [Challenge](#challenge)
* [User Story](#user-story)
* [Acceptance Critiera](#acceptance-criteria)
* [Walk Through](#walk-through)
* [License](#license)

### Challenge:
This challenge is to build the back end for an e-commerce site. I will take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## User Story
> AS A manager at an internet retail company\
> I WANT a back end for my e-commerce website that uses the latest technologies\
> SO THAT my company can compete with other e-commerce companies
## Acceptance Criteria
> GIVEN a functional Express.js API\
> WHEN I add my database name, MySQL username, and MySQL password to an environment variable file\
> THEN I am able to connect to a database using Sequelize\
> WHEN I enter schema and seed commands\
> THEN a development database is created and is seeded with test data\
> WHEN I enter the command to invoke the application\
> THEN my server is started and the Sequelize models are synced to the MySQL database\
> WHEN I open API GET routes in Insomnia Core for categories, products, or tags\
> THEN the data for each of these routes is displayed in a formatted JSON\
> WHEN I test API POST, PUT, and DELETE routes in Insomnia Core\
> THEN I am able to successfully create, update, and delete data in my database

## Walk Through

## Installation Instructions:

This requires express.js, node.js, mysql2 and sequelize. Open the terminal and begin with ```npm init``` followed by ```npm i``` to hopefully automatically install all required dependencies. If it fails, manually install each with  ```npm i express```, then ```npm i mysql2``` followed by ```npm i sequelize```, and ```npm i dotenv```. You will need to make your own .env file to connect to the DB as one is not included.  As node modules are not included in this repo. This will allow for full functionality.

Run the program by opening your terminal in the main folder and typing ```node index.js```

## Usage:

To dynamically manage a e-commerce backend consisting of categories, products and tags. 

## Contributing:

Add on!

## License:

ISC 2022

## Github Account:

  Click here: https://github.com/edirie
