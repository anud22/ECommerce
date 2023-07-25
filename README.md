 # E-Commerce Back End - ORM
 <br>

 ## Table Of Contents
- [Description](#description)
- [Installation](#installation)
- [Video](#video)
- [References](#references)
<br>
<br>

 ## Description
This project builds the back end for an e-commerce site by modifying starter code. It uses Express.js API and Sequelize to interact with a MySQL database. The database contain the following four models - Category, Product, Tag, ProductTag. `Product` belongs to `Category`, and `Category` has many `Product` models, as a category can have multiple products but a product can only belong to one category.`Product` belongs to many `Tag` models, and `Tag` belongs to many `Product` models. Allow products to have multiple tags and tags to have many products by using the `ProductTag` through model.
User can perform create, read, update, and delete API operations for Product, Category, Tag.


## Installation
To run project locally follow these steps - 
1. Run npm i to install the required packages
2. Run schema.sql and seeds.sql to create tables and seed data.
3. Run npm start to start express server.


## Github Link
Github link to access the project is [Github URL](https://github.com/anud22/ECommerce)


## Video
[Project video](https://drive.google.com/file/d/10to1yp9Wz5TrZye7ny2XWKzStn9ivP9C/view)
 
 ## Questions
 #### If you have any questions or need further clarification, feel free to reach out. We are here to help! You can ask questions by creating an issue in this repository or by reaching out to me 
Github profile (https://github.com/anud22)