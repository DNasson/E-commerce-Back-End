# E-commerce-Back-End

## Description

User Story

AS A manager at an internet retail company <br>
I WANT a back end for my e-commerce website that uses the latest technologies <br>
SO THAT my company can compete with other e-commerce companies <br>
Acceptance Criteria <br>
GIVEN a functional Express.js API <br>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file <br>
THEN I am able to connect to a database using Sequelize <br>
WHEN I enter schema and seed commands <br>
THEN a development database is created and is seeded with test data <br>
WHEN I enter the command to invoke the application <br>
THEN my server is started and the Sequelize models are synced to the MySQL database <br>
WHEN I open API GET routes in Insomnia for categories, products, or tags <br>
THEN the data for each of these routes is displayed in a formatted JSON <br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia <br>
THEN I am able to successfully create, update, and delete data in my database <br>

The motivation behind this project was to give a back end the uses the latest technologies. 
The project was built because it provides a database that creates, deletes, and updates data. 
By having the latest technology the company using this application can compete with other companies that specialize in e-commerce.
I learned how to link code between routes, seeds, and models so that they can all work together to create a database. I learned the syntax for making the GET, POST, PUT and DELETE requests so they will do what is needed for the user. 


## Installation

Utilize the green code button on the repository and copy the "SSH Key" into your terminal after 'git clone'

## Usage
After downloading the code from the repository run mysql -u root -p in the db folder and source the "schema.sql" file. Use "control z" to suspend mysql and use "cd .." to get to the root of the project. Run "npm i", "npm run seed", and "node server.js" to open the server on the port given. Open insomnia and put in GET, PUT, POST, and DELETE commands according to the routing outlined to run the correct sequences.

Run-through: https://watch.screencastify.com/v/63rlVT8gsWUVLxRB01rx 

GitHub Repository: https://github.com/DNasson/E-commerce-Back-End

## Credits

Starter Code: https://utah.bootcampcontent.com/utah-coding-bootcamp/UofU-VIRT-FSF-PT-02-2023-U-LOLC/-/tree/main/01%20-%20Class%20Content/13-ORM/02-Challenge/Develop 

## License

MIT License
