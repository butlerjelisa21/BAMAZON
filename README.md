# BAMAZON

Created during Week 12 of SMU Coding Bootcamp. The goal was to create an Amazon-like store front using Node.js and MySQL.

Getting Started

1. Clone repo.
2. Run command in Terminal or Gitbash 'npm install'
3. Run command depending which mode you would like to be on:
	Customer - 'npm run customer'
	Manager - 'npm run manager'
	Exective - 'npm run exective'
•	Run 'ctrl + c' to exit each mode

# What Each JavaScript Does
1.bamazonCustomers.js
	Prints the products in the store.
	Prompts customer which product they would like to purchase by ID number.
	Asks for the quantity.
	If there is a sufficient amount of the product in stock, it will return the total for that purchase.
	However, if there is not enough of the product in stock, it will tell the user that there isn't enough of the  product.
	If the purchase goes through, it updates the stock quantity to reflect the purchase.
	It will also update the product sales in the department table.
 
2.	bamazonManager.js
Starts with a menu:
View Products for Sale
	View Low Inventory
	Add to Inventory
	Add New Product
	End Session
	If the manager selects View Products for Sale, it lists all of the products in the store including all of their details.
	If the manager selects View Low Inventory, it'll list all the products with less than five items in its Stock Quantity column.
	If the manager selects Add to Inventory, it allows the manager to select a product and add inventory.
	If the manager selects Add New Product, it allows the manager to add a new product to the store.
	If the manager selects End Session, it ends the session and doesn't go back to the menu.

# Technologies used
•	Node.js
•	Inquire NPM Package (https://www.npmjs.com/package/inquirer)
•	MYSQL NPM Package (https://www.npmjs.com/package/mysql)

# Prerequisites
- Node.js - Download the latest version of Node https://nodejs.org/en/
- Create a MYSQL database called 'Bamazon', reference schema.sql

# Built With
•	Sublime Text - Text Editor
•	MySQLWorkbench
•	Terminal/Gitbash

# Authors
•	Jelisa Butler - JS/MySQL/Node.js – Jelisa Butler 

