# Unit 13: ORM E-Commerce Back-End
## Description

The task for this unit was to build out the back end for an e-commerce website using provided starter code and configuring a working Express.js API and Sequelize to interact with a MySQL database.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Screenshot](#screenshot)
- [Walkthrough Video](#walkthrough-video)
- [Credits](#credits)
- [License](#license)

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
```

## Screenshot
This is a screenshot of t

![Team Generator HTML Webpage Screenshot](./assets/Team-Profile-Generator_Screenshot.png)

## Walkthrough Video
The purpose of the walkthrough was to demonstrate that all technical acceptance criteria for the project were being met. This included:
1. Creating the schema from the MySQL shell
2. Seeding the database from the command line
3. Starting the application's server
4. Demonstrating all GET routes for all categories, all products, and all tags (tested in Postman)
5. Demonstrating GET routes for a single category, a single product, and a single tag (tested in Postman)
6. Demonstrating POST, PUT, and DELETE routes for categories, products, and tags (tested in Postman)

![E-Commerce Back-End Walkthrough Video](./assets/10_OOP-Team-Profile-Generator-Demo_Final.gif)
## Credits
- Trilogy Education Services, LLC: https://www.trilogyed.com/ 
- MySQL2: https://www.npmjs.com/package/mysql2
- Express.js: https://expressjs.com/
- Sequelize: https://www.npmjs.com/package/sequelize
- dotenv: https://www.npmjs.com/package/dotenv
- Postman: https://www.postman.com/

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

MIT License

Copyright (c) 2021 James L. Jenks

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