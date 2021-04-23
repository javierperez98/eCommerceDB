# Employee Tracker

![MIT](https://img.shields.io/github/license/microsoft/vscode)

## Description

<!-- Provide a short description explaining the what, why, and how of your project.
What was your motivation? Why did you build this project? What problem does it solve? What did you learn? -->

-

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Questions](#questions)

## Installation

<!-- What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running. -->

### To install copy and paste either the SSH or HTTPS key and run it in either Bash (PC Users) or Terminal (MAC Users) using the git clone command.

```md
SSH key: git clone git@github.com:javierperez98/eCommerceDB.git
HTTPS key : git clone https://github.com/javierperez98/eCommerceDB.git
```

### Next you'll have to install all the required node modules by opening the server.js file using terminal/bash and typing in the following command.

```md
npm i
or
npm install
```

### Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands.

MYSQL Database

```md
DROP DATABASE IF EXISTS ecommerce_db;
CREATE DATABASE ecommerce_db;
```

### Create a dotenv file to store sensitive data like your MySQL username, password, and database name.

Dotenv File

```md
DB_USER = root
DB_PW =
DB_NAME = ecommerce_db
```

### Once the Database is created, seed all the information into the database by running this command in the terminal of server.js

```md
npm run seeds
```

## Usage

<!-- Provide instructions and examples for use. Include screenshots as needed. -->

### Video Demo of App: [Click Here]()

When you want to launch the application open server.js in the terminal and run the command to start

```md
npm start
```

![Command NPM Start should look like this in the terminal](Assets/npmStart.png)

Next use a program like Insomnia to get, add, update and delete information to and from the database.

![]()

## Credits

<!-- List your collaborators, if any, with links to their GitHub profiles. Links to websites or resources. -->

- https://www.google.com
- https://nodejs.org
- https://developer.mozilla.org/en-US/
- https://w3schools.com
- https://expressjs.com/
- https://stackoverflow.com/
- https://www.mysql.com/
- https://sequelize.org/
- https://www.npmjs.com/package/mysql2

## License

<!-- If you need help choosing a license, refer to https://choosealicense.com/ -->

MIT License

Copyright (c) 2021 [Javier Perez]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Questions

Contact me for any questions you might have.

- GitHub: [javierperez98](https://github.com/javierperez98)
- Email: [javier21perez98@gmail.com](mailto:javier21perez98@gmail.com)
- LinkedIn: [javierperez98](https://www.linkedin.com/in/javier-perez98/)
