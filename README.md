# E-Commerce Back End 
 
## Description
Creating a working Express.js API and configuring it to use Sequelize to interact with a MySQL database. 
https://www.youtube.com/watch?v=MT-_dzim4GU

## Table of Contents
[Installation](#installation)
[Usage](#usage)
[Contributing](#contributing)
[Tests](#tests)
[Questions](#questions)
[License](#license)   

## Installation
Copy/Download/Clone the repository to your designated folder. 

## Usage
This project is used to display the ability to Create, Read, Update, and Delete information from an Express.js API. 

## Contributing
You can fork the project from my GitHub account and follow the installation instructions. My git hub and email are detailed below.

## Tests
To test the program it is best to make sure the data has run and filled appropriately. In the server.js file on line 15 change the ({ force: false }) value to ({ force: true }). After that is completed run the program by prompting (npm node server.js) alternatively, you may type (npm start) if the scripts section has the start command. Once the program has started allow the program to drop and replace all existing databases. This is to ensure that there are no missing items/data in the databases. Once that has completed return to the server.js file and switch ({ force: true }) value to ({ force: false }). This will prevent the server from dropping the database information on the next server start. Next, we will provide the databases with data. Run the (npm run seed) command to fill the data in the databases. Once this has been completed you may test the program with (npm node server.js or npm start). 

## License
This project is under the [NONE](https://opensource.org/licenses/NONE) license.

## Questions
If you want to contact me you can reach me at zinanshin.kaoher@gmail.com or checkout my GitHub account at [kaohzina](https://github.com/kaohzina).
