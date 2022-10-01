# 13 Object-Relational Mapping (ORM): E-Commerce Back End

# ReadMe E-Commerce Back End

The task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

The application will be invoked by using the following command:

node server.js

Include a video of the typical user flow through your application. This includes views of the prompts and the responses after their selection.


A walkthrough video that demonstrates the functionality of the note taker app.



# Screenshots


<img src="./assets/images/screen_appview.png">


<img src="./assets/images/note_screen.png">



### API Routes Tested

Products
	getAllProducts  		http://localhost:3001/api/products/

	getSingleProduct  	http://localhost:3001/api/products/3

	addNewProduct  		http://localhost:3001/api/products/

	updateSingleProduct  	http://localhost:3001/api/products/4

	deleteSingleProduct  	http://localhost:3001/api/products/1

	
Categories
	getAllCategories		http://localhost:3001/api/categories/

	getSingleCategory 	http://localhost:3001/api/categories/3

	addNewCategory 		http://localhost:3001/api/categories/

	updateSingleCategory 	http://localhost:3001/api/categories/4

	deleteSingleCategory	http://localhost:3001/api/categories/1

	
Tags
	getAllTags			http://localhost:3001/api/tags/

	getSingleTag 		http://localhost:3001/api/tags/3

	addNewTag 	 		http://localhost:3001/api/tags/

	updateSingleTag 	 	http://localhost:3001/api/tags/4

	deleteSingleTag 		http://localhost:3001/api//tags/1

	

## User Story

AS A manager at an internet retail company

I WANT a back end for my e-commerce website that uses the latest technologies

SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria


GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an
 environment variable file

THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands

THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application

THEN my server is started and the Sequelize models are synced to the MySQL
database

WHEN I open API GET routes in Insomnia for categories, products, or tags

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia

THEN I am able to successfully create, update, and delete data in my database


# Link to walkthrough video (YouTube)

https://youtu.be/Kdo1DHAN8Sc


# App Github Deploy Link


https://github.com/Trebligony/ecommerce-backend






