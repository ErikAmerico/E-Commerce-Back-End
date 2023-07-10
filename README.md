# E-Commerce Back End

## Description
This is an application designed to allow a user to create, read, update and delete certain categories, products and tags of their choosing. It would be good tool for a business owner to keep track of and manage their inventory.

## Installation
To use this application on your local machine, you would have to:

-Clone the repository down from github.

-Be sure to have node.js installed.

-Open the terminal and run 'npm install' to install the required dependencies that are found in the package.json file.

## Usage
To run this program:

-After running 'npm install', in the same terminal do the following:

-Run the command 'mysql -u root'. This will sign you into mysql (no password is set for ease of use).

-Run the command 'source db/schema.sql;'. This will create the database and tables.

-Run 'exit', to exit mysql and execute the following commands:

-Run the command 'node seeds/index.js'. This will seed the database with the Categories, Products and Tags.

-Run the command 'node server.js', This will sync sequalize models to MYSQL database and start the server.

-You can use Insomnia test the applications functionality.

[Link to Insomia application website](https://docs.insomnia.rest/)

## Link to walkthrough video
[Walkthrough](https://watch.screencastify.com/v/It6G7MyHAY8IoG9Nxujy)

## Link to GitHub Repository
[Github](https://github.com/ErikAmerico/E-Commerce-Back-End)
 
## Screenshots
This shows the executed route for retrieving all categories. 

![Show Categories](Assets\InsomniaApiCategories.png)

This shows the executed route for creating a new product.

![Create Product](Assets\InsomniaApiCreateProduct.png)

## Contact

GitHub: [ErikAmerico](https://github.com/erikamerico)
    
Email: erikamerico1991@gmail.com