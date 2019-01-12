# eat-da-burger
A Burger Eatin' Application With Node.js/Express/MySQL/Handlebars/Materialize

## Description

This is an applciation that will log burgers with MySQL, Node, Express, Handlebars and a homemade ORM (yum!).

The user may enter any burger name to add it to the menu. This also adds the new burger entry into the MySQL database. The initial burger entry is added as *available* on the menu and placed on the left side of the screen. The user may then eat any burger by clicking on it, which moves it into the adjacent column and updates its status accordingly in the database.

## Installation

To run the application locally, first clone this repository with the following command.

	git clone https://github.com/joshmoore2003/eat-da-burger.git

Next, install the application dependencies.

	npm i
	
Finally, run the node server locally.

	node server.js
	
Now, open the local application on port 3000 at the URL: `http://localhost:3000/`.

**Enjoy and have a burger!**
![burger photo](/public/assets/img/eat-da-burger.png)