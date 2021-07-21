# ORM E-Commerce Back-End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
* [Description](#description)
* [Lessons Learned](#lessons-learned)
* [Installation](#installation)
* [Usage](#usage)
* [Tools](#tools)
* [How to Contribute](#how-to-contribute)
* [License](#license)
* [Questions](#questions)

## Description 
This is the back-end framework for an e-commerce application. Once connected with the front-end of the application, this will allow users to view, add, update, or delete products, categories, and tags.  
This portion of the application uses express and sequelize to connect the user actions to the database.

## Lessons Learned
In working on this project I learned more about developing models and api routes to organize, structure, and pass data/requests between the user interface and the database. 

## Installation
To install, clone the repository and then run "npm i" in the terminal to install dependencies.

## Usage
To use the application, create the database in MySQL using the code in the schema.sql file. You will need to create a .env file with the user and password for your MySQL account. A sample file is included as a reference. Once that is created, run "npm start" in the terminal to connect to the server. Since there is no front-end framework set up for this application, to test and use the application you will need to create POST, GET, PUT, and DELETE methods in Insomnia with routes to the relevant api. 
 
  ### Demo
  ![Demo](./Assets/E-Commerce_Back-end.gif)
  
  The demo video can be viewed here as well: https://youtu.be/jINljpSZJFQ

## Tools
<img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node-dot-js&logoColor=white"/>  <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>  <img alt="Markdown" src="https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white"/>  <img alt="Visual Studio Code" src="https://img.shields.io/badge/VisualStudioCode-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>  <img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>  <img alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"/>  <img alt="npm-epxress" src="https://img.shields.io/badge/npm:express-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white"/>  <img alt="npm-sequelize" src="https://img.shields.io/badge/npm:sequelize-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white"/>  <img alt="Insomnia" src="https://img.shields.io/badge/npm:Insomnia-%235849BE.svg?style=for-the-badge&logo=insomnia&logoColor=white"/>'

## How to Contribute
If you would like to contribute, please follow the relevant steps outlined here: https://www.dataschool.io/how-to-contribute-on-github/ or send feedback to Sandy Marr.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright 2021 Sandra Marr

  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
  
  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
  
  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Questions

For any questions, please contact Sandra Marr: [GitHub](https://github.com/sandra-marr) or [Email](srpeters44@gmail.com)
