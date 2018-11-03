# Bamazon

Before beginning program
  Download the latest version of Node https://nodejs.org/en/
  Using MYSQL, create a database called 'Bamazon'. 
    - Reference schema.sql

Getting Started
  Run command in Terminal or Gitbash 'npm install'
  Run command depending which mode you would like to be on:
    Customer - 'npm run customer'
    Manager - 'npm run manager'
Run 'ctrl + c' to exit each mode

What The JavaScript Does

BamazonCustomer.js

  - Will print the products in the store.
  - Asks the customer which product they would like to purchase by ID number.
  - Asks for the quantity.

If there is a enough of the product in stock, it will return the total for that purchase.
If there is not enough of the product in stock, it will tell the user that there isn't enough of the product.
If the purchase goes through, it updates the stock quantity to reflect the purchase.
It will also update the product sales in the department table.

BamazonManager.js

  Starts with a menu:
    - View Products for Sale
    - View Low Inventory
    - Add to Inventory
    - Add New Product
    - End Session

If the user selects View Products for Sale, it lists all of the products in the store including all of their details.
If the user selects View Low Inventory, it'll list all the products with less than five items in its StockQuantity column.
If the user selects Add to Inventory, it allows the manager to select a product and add inventory.
If the user selects Add New Product, it allows the manager to add a new product to the store.
If the user selects End Session, it ends the session and doesn't go back to the menu.

