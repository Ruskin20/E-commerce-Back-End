# E-Commerce Back End
[![License: GPL v3](https://img.shields.io/badge/license-MIT-red)](https://www.gnu.org/licenses/gpl-3.0)

## Description
Developers frequently have to create interfaces that allow non-developers to easily view and interact with information stored in databases. These interfaces are called content management systems (CMS). This app is a command-line application that manages a company's employee database, using Node.js, Inquirer, and MySQL.
## Description
```md
Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes.

This app uses mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.
```
## Table of contents
* [Installation](#Installation)
* [Usage](#Usage)
* [Visuals](#Visuals)
* [Links](#Link)
* [License](#License)

## Installation

You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.
## Visuals

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)

## Links 
You could view the application by clicking on the link below:


## License
[MIT LICENSE](https://raw.githubusercontent.com/Ruskin20/E-commerce-Back-End/master/LICENSE)