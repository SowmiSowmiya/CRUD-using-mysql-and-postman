
# Node.js, MySQL & Express: Simple Add, Edit, Delete, View (CRUD)

Here’s the step-by-step procedure to create the CRUD application:

1) Open terminal/command-prompt and go to your Node.js project directory. Mine is `/var/www/html/test/nodejs/crud-mysql`

              cd /var/www/html/test/nodejs/crud-mysql
              /var/www/html/test/nodejs/crud-mysql

2) Run `npm init` command in terminal that will create package.json file for your project.

3) Install Express Framework module with the following command: 

         npm install express -save

4) Install `express-validator` module that will be used for form validation

             npm install express-validator -save

5) Install `body-parser` module
       
            npm install body-parser -save

6) Install `method-override` module
  
           npm install method-override -save

7) Install `express-flash` module

          npm install express-flash -save

8) Install MySQL module with the following command:

         npm install mysql -save

9) As you see in `app.js` code, our server runs on port 3000. Hence, to use the application, we have to run the following URL on browser: http://127.0.0.1:3000




