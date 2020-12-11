# burger-12.8.20

## About The Project

---

![alt text](public/assets/Images/image1.PNG)

![alt text](public/assets/Images/image2.PNG)

![alt text](public/assets/Images/image3.PNG)

-    Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

-    Whenever a user submits a burger's name, app will display the burger on the left side of the page -- waiting to be devoured.

-    Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.

-    Your app will store every burger in a database, whether devoured or not.

## Implemented the following functionalities

-    selectAll()
     -    Retrieve all burgers from database by executing SELECT staement and didplay on the UI.
-    insertOne()
     -    Add the burger to burgers table in database when user enter the burger name and click on submit button by executing INSERT statement
-    updateOne()
     -    Update the burger's devoured state from false to true and display in UI by executing UPDATE statement

## Built With

-    express
-    express-handlebars
-    mysql
-    dotenv

## Getting Started

To get a local copy up and running follow below steps.

## Prerequisites

None

## Installation instructions:

Clone the repo git clone git@github.com:NirmalaAbothu/burger-12.8.20.git then open Git Bash window ,navigate to project folder then run
following commands

-    Make a package.json file by running `npm init` from the command line.

-    Install the Express npm package: `npm install express`.

-    Install the Handlebars npm package: `npm install express-handlebars`.

-    Install MySQL npm package: `npm install mysql`.
-    Install dotenv package: `npm install dotenv`

## Credits

Followed the documentation about mysql

## License & copyright

Copyright © 2020 Nirmala Abothu
