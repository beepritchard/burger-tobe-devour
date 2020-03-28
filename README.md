# Delicious Burger
MVC Burger application that allows you to create burgers (POST), view a list of burgers available to eat (GET), devour burgers (PUT), and throw them away after devoured (DELETE).</p>
<img src="./public/assets/img/devour.png">


### Technologies used:
  * Backend technologies
    * [Node.js](https://nodejs.org/en/)
    * [MySQL](https://www.mysql.com/)
    * [Express](http://expressjs.com/)
    * [ORM - Object Relational Mapping](https://en.wikipedia.org/wiki/Object-relational_mapping)

  * Frontend technologies
    * HTML
    * CSS
    * [Bootstrap](http://getbootstrap.com/)
    * Javascript
    * [jQuery](https://jquery.com/)
    * [Handlebars](http://handlebarsjs.com/)

### How this app works:
This application allow you to place an order for a burger. When you place an order, the burger you enter in the form field is added to the list of burgers on the left side of the screen. Each burger in the list has a <b>Devour me</b> button. Clicking this button moves the burger from the list on the left side of the screen to the list on the right. The list on the right is a list of burgers that have already been devoured. Each burger in this list has a <b>Throw away</b> button that allows you to remove the burger, which deletes the burger from the user interface as well as from the MySQL database. 


To set up this application locally on your computer, perform the following steps:
  1. Clone the repository
  2. Install Node.js
  3. Install the dependencies
  4. Install MySQL Workbench
  5. Set up a development database
  6. Create a .env file to store your MySQL Password
  7. Verify database connection information
  8. Start the server

Application improvements
* Add a form field that allows users to provide their name with the burger they ordered.
* Allow users to update a burger's name after it is created.
* Add form validation so that the user can't submit an empty form
