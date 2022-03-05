# E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---
## Description

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. 

This is an example back end for an e-commerce site. The project uses Express.js API and Sequelize to interact with a MySQL database.


### Database Models

This database contain the following four example models:

* `Category`

  * `id`
  * `category_name`

* `Product`

  * `id`
  * `product_name`
  * `price`
  * `stock`
  * `category_id`

* `Tag`

  * `id`
  * `tag_name`

* `ProductTag`

  * `id`
  * `product_id`
  * `tag_id`

---
## Table of Contents

- [Installation](##Installation)

- [Usage](##Usage)

- [License](##License) 

- [Tests](##Tests)

- [Questions](##Questions)

---
## Installation

- First, use git clone in the terminal to download the project 
- Then open the project in VS Code and in the package.json folder enter the terminal 
- Within the terminal, use npm install install to install the all packages
- Open Mysql in terminal and run the schema.sql file to create the database
- Run `npm run seed` to seed data to your database so that you can test the routes.
- The routes can be tested by using Insomnia

---
## Usage

For learning about database 

### Screenshot:
![alt text](assets/img/ScreenShot1.png)

### Walkthrough Video:
[![Watch the video](assets/img/ScreenShot2.png)]()


--- 
 
 ## License 
 
 https://opensource.org/licenses/MIT

---
## Tests

There are no tests for this application.

---
## Questions

If you have any questions or concerns please contact me at bxz5089@gmail.com or checkout my GitHub page at [bxz5089](https://github.com/bxz5089/).

