# E-Commerce Back End

## Description
This application uses mysql and sequelize to create an e-commerce back end.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Questions](#questions)

## Installation
This application requires: 
- nodeJS: ([download and read the documentation here](https://nodejs.org/en/download/)) 
- mysql: ([download and read the documentation here](https://dev.mysql.com/doc/))
- dotenv: ([download and read the documentation here](https://www.npmjs.com/package/dotenv))
- sequelize: ([download and read the documentation here](https://sequelize.org/))

## Usage
Clone the repository and create a '.env' file. Enter your mysql information to authenticate access to mysql. An example can be found in the '.env.EXAMPLE' file.
In the terminal, type the below command. and enter your mysql password to connect:<br>
`mysql -u root -p`
<br>

Next, source the database file by entering the below into mysql:<br>
`source ./db/schema.sql`
<br>

If your database has successfully been created, quit mysql. Install node to the application and run the seed data:<br>
`npm install`
`npm run seeds`

Confirm that tables and created and seeded in MySQL.<br>

In the terminal, type the below command:<br>
`npm start`
<br>

The application will now be running on port 3001. You can get, add, update and delete data from the categories, products and tag tables.<br>


[Click here for a demonstration video of this application!](https://drive.google.com/file/d/1zy7vwoWW9T5ScHgsyyjVLkYpxIwJs5CH/view?usp=sharing)

## Credits
Starter code from UToronto Coding Boot Camp. The repository can be accessed [here](https://github.com/coding-boot-camp/fantastic-umbrella)

## License
[![MIT License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <br>
This application is covered under the MIT license. To learn more, visit the link [here!](https://opensource.org/licenses/MIT)

## Questions
Questions? My Github is [here](https://github.com/phoenixouyang)
