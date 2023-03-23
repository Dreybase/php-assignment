# API_project
This is a PHP assignment to create a RESTful API.

# API_project Requirements
API tester (POSTMAN), XAMMP

# Installation
Clone/Download the project file to the htdoc server directory  
Create a database in the localhost/phpmyadmin panel called "clothing-api"
Import the sql database in the config folder
Make sure the database details specified in the config/Database.php file matches with the apache web-server detais.
On Linux OS, make sure to activate the PDO 

# Running\
 Open and create a new http request in your POSTMAN application 

 # End point 
 http://localhost/API_project/api/products/read_single.php?product_id=5
 To read a single product from the products table in the database column by passing the product_id parameter
 
 http://localhost/API_project/api/products/read.php
 To read all the product from the database 

  http://localhost/API_project/api/products/read_single.php?customer_id=3
  To read a single customer from the customers table in the database column by passing the product_id parameter

  http://localhost/API_project/api/customer/read.php
 To read all the customers from the database 

 http://localhost/API_project/api/order/read_single.php
  To read a single order from the order table in the database column by passing the product_id parameter

 http://localhost/API_project/api/orders/read.php
 To read all the orders from the database 
 
