# Online Shopping Cart 


An online shopping cart application developed using PHP, JavaScript, CSS, and other technologies. This project allows users to browse products, add them to the shopping cart, and proceed with the checkout process. The application is designed to provide a seamless online shopping experience.

# Features :

Product Browsing: View a list of products with detailed descriptions, prices, and images.
Add to Cart: Add products to the shopping cart with adjustable quantities.
Shopping Cart Management: View the items in the cart, modify quantities, and remove items.
Checkout: Proceed to checkout, providing user details and payment options.
Responsive Design: Optimized for both desktop and mobile devices.
User Authentication: Option to create an account, login, and track orders.
Admin Panel: Manage products, orders, and users.

# Technologies Used :

PHP: Backend logic and server-side processing.
JavaScript: Frontend interactivity, including dynamic cart updates.
HTML: Structure of the webpage.
CSS: Styling and layout of the application.
MySQL: Database for storing products, user data, and orders.
Ajax: For making asynchronous requests without page reloads.
Bootstrap (Optional): For responsive and modern UI components.

# Installation :

Prerequisites
PHP version 7 or higher.
MySQL or MariaDB database.
Web server (e.g., Apache, Nginx).
Steps

# Clone this repository to your local machine :

git clone https://github.com/DarkHacker28/Online_Shopping_Cart
Set up a local web server (e.g., Apache) and make sure PHP is installed.

Create a MySQL database and import the provided database.sql file:

CREATE DATABASE shopping_cart;
Then, import the schema and initial data from database.sql.

Update the database connection details in config.php:

define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_DATABASE', 'shopping_cart');

Ensure the assets folder contains the necessary product images, CSS, and JavaScript files.

# Open the project in a web browser :

http://localhost/online-shopping-cart/index.php

# File Structure :

/online-shopping-cart
├── /assets
│   ├── /css
│   ├── /images
│   └── /js
├── /includes
│   ├── db.php
│   ├── header.php
│   ├── footer.php
│   └── cart-functions.php
├── /public
│   ├── index.php
│   └── checkout.php
├── /admin
│   ├── login.php
│   ├── dashboard.php
│   └── manage-products.php
├── /config
│   └── config.php
└── /database.sql

# Usage :
Homepage: Displays a list of products available for purchase.
Cart: Users can add/remove products and adjust quantities. The cart is stored in a session.
Checkout: Users can enter shipping details and complete the purchase.
Admin Panel: Admins can log in to manage products and orders.


# Contributing :

Fork this repository.
Create a feature branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

# Acknowledgements :
Bootstrap for the frontend design framework.
Font Awesome for the icons.
PHP Manual for guidance on PHP functions.


# Customizations :
Feel free to replace placeholders like https://github.com/DarkHacker28/Online_Shopping_Cart.git with your actual GitHub link, and add any specific configuration steps based on your application’s unique features.
