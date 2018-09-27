# Burger
Burger Bucket List! is a restaurant app that lets users input the names of burgers they'd like to eat. 

# Node Express Handlebars

## Burger-Bucket-List Deployment on Heroku - https://enigmatic-refuge-91564.herokuapp.com/

### Overview

In this application, I have created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). I have leveraged the MVC design pattern; using Node and MySQL to query and route data in my app, and Handlebars to generate my HTML.

### What does Burger do?

* Burger Bucket list! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, my app will display the burger on the left side, "The Top Bugers on the Menu: Click to devour" of the page -- waiting to be devoured.

* Each burger in the "The Top Bugers on the Menu: Click to devour" waiting area can be devoured by clicking on one of the lists burger represented as buttons. When the user clicks it, the burger will move to the right side of the page in the "Burgers You Have Already Devoured: Click to Delete" area.

* Whenever a user clicks on the list of buttons on the right under the "Burgers You Have Already Devoured: Click to Delete" area, my app will delete the devoured burger from the list.

* My app stores every burger in a database, whether devoured or not.

#### Directory structure

All the recommended files and directories from the steps above should look like the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
### Burger-Bucket-List Application
---
   ![Image API Eat-Da-Burger Home](https://github.com/jhwillia7/Burger/blob/master/public/assets/img/Burger%20Initial%20Page.PNG)
---
- - -

- - -

- - -