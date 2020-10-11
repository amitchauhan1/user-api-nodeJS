# user-api-nodeJS
Only for testing
We will build Rest Apis for creating, retrieving, updating & deleting Customers.
First, we start with an Express web server. Next,
we add configuration for MySQL database, create Customer model,
write the controller. Then we define routes for handling all CRUD operations:

$ mkdir nodejs-express-mysql
$ cd nodejs-express-mysql

npm init

name: (nodejs-express-mysql) 
version: (1.0.0) 
description: Node.js Restful CRUD API with Node.js, Express and MySQL
entry point: (index.js) server.js
test command: 
git repository: 
keywords: nodejs, express, mysql, restapi
author: bezkoder
license: (ISC)

Is this ok? (yes) yes

--------------------------------------------------------------------------
Next, we need to install necessary modules: express, mysql and body-parser.
Run the command:
============================================
npm install express mysql body-parser --save
============================================
Now we can run the app with command: node server.js.
Open your browser, enter the url http://localhost:3000/

------------------------------------------------------
https://bezkoder.com/node-js-rest-api-express-mysql/
------------------------------------------------------
