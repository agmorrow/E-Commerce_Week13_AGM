# E-Commerce_Week13_AGM
![GitHub license](https://img.shields.io/badge/license-MIT-yellow.svg)
## Description
I was given a task to build the back end for an e-commerce site by modifying starter code. I configured a working Express.js API to use Sequelize to interact with my MySQL database. When logged into an API Platform like Insomnia or Postman, a user can search using a GET route to see products, categories, or tags. They can also search for by individual ids. There are also features to test POST, PUT, and DELETE routes to successfully create, update, and delete data in teh database.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation
- Make sure node.js and MySQL are installed:
```bash
https://nodejs.org/en/download/

npm i msql2
** It is also important to have a SQL GUI installed and match the config folder to the users SQL connection information.
```
- Make sure you install node_modules to your file
```bash
npm i
```

- Seed the database:
```bash
npm run seed
```

- Run the server using the following command:
```bash
node server.js or nodemon server.js (if you have nodemon installed)
```


## Usage

### Walk through video

<a href="#" target="_blank">Walk through video</a>

### Screenshots





## Credits
DU Bootcamp Lectures - Week 13

## License

Copyright (c) 2022 Austin Morrow

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