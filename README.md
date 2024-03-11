# ECOMbe

## Table of Contents
1. Project Description
2. User Story
3. Acceptance Critera
4. Programs Used
5. Installation
6. Credits
7. License
8. Contact

## 1. Project Description
This is a back end for an e-commerce site. It uses Express.js API and Sequelize to interact with a MYSQL database. It is deployed on Heroku.

## 2. User Story
- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies

## 3. Acceptance Criteria
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia Core for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
- THEN I am able to successfully create, update, and delete data in my database



## 4. Programs Used
1. Node.js
2. mySQL
3. Express.js
4. Sequelize 
## 5. Installation

1. Clone the repository: "git@github.com:paigepreziosi/ECOMbe.git"
2. Install the necessary dependencies by running "npm install" in the terminal
3. Run the following command at the top level of your directory: "mysql -u root -p"
4. Enter your MySQL password
4. Run the following command to create the database: "source db/schema.sql"
5. Run the following command to seed the database: "npm run seed"
6. Run the following command to start the server: "npm start"
7. Open Insomnia Core to test the API routes

## Credits

N/A

## License

N/A

## Contact

Name: Paige Preziosi
E-mail: PVPreziosi@hotmail.com
GitHub: https://github.com/paigepreziosi
