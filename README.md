# E-commerce-Back-End Created by Jeancarlos Mulet w/ 🙌 The University of Miami 🙌

## Description

 mysql database/application backend for an e-commerce website ,using MySQL2, Express, Sequelize and dotenv. repository includes tests!

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Questions](#questions)

## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```


## Installation

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage  
  
Run `mysql -u root -p` at the root of your repository 

Enter local root PW.

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

![SCREENSHOT1](https://github.com/JCLOS305/E-commerce-Back-End/blob/main/assets/images/GET%20routes%20single%20categories.gif?raw=true)
![SCREENSHOT2](https://github.com/JCLOS305/E-commerce-Back-End/blob/main/assets/images/GET%20routes.gif?raw=true)
![SCREENSHOT3](https://github.com/JCLOS305/E-commerce-Back-End/blob/main/assets/images/PUT%20DELETE%20POST.gif?raw=true)

## Testing

No testing is set up



## Credits

For this Challange I referenced my code in a similar project and my modules in class, Youtube, Google, Instructions from my Class TA's

- Jordan 
- Jocelyn 
- Tim 
- Cristian 

and directions from my Instructor

- Felicia O'Garra

for this specific assignment I had help from 2 of my classmates 

In order of apperance 

[Alex Noble-James](https://github.com/alexnj1)

[Wilmer Ojeda](https://github.com/wilmerojeda13)

[PLEASE GIVE THEM A FOLLOW THEY ARE AMAZING DEVELOPERS]

## License

MIT License

Copyright (c) 2022 Jeancarlos

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


## Badges

![JCLOS305](https://img.shields.io/badge/Orchestrated%20by-JCLOS305-blue)
![UOM](https://img.shields.io/badge/University%20of-Miami-orange)


© March 2022 Jeancarlos Mulet - University of Miami
