# Just Tech News

## Description
Just Tech News is a tech news website where users can post, upvote, and comment on links to news articles.
This project build the back end of the website. 

## Technologies

* ORM object-relational mapping, a technique that allows developers to convert data between incompatible type systems using object-oriented programming principles. 
* Node.js

    * Sequelize, an object-relational mapping (ORM) library, is used to simplify MySQL queries, add password hashing so that users can create secure passwords

    * Dotenv is a zero-dependency Node.js module that loads environment variables from a .env file into process.env, a Node.js property that returns an object containing the user environment. This allows developers to store user environment configuration—or the things that are likely to vary between different deployments (passwords, secrets, keys, etc.)—separately from their code.

    * bcrypt is a Node.js library that allows to hash passwords. Hashing is the process of taking input and using a mathematical formula to chop and mix it up to produce an output of a specific length. Hashing is a one-way function, meaning that it can easily convert input to a fixed-size output, but it is difficult to invert, or convert in the opposite direction. This attribute allows developers to secure passwords when authenticating users for their applications.

* Heroku : deployed in Heroku  https://shrouded-springs-72029.herokuapp.com
* JawsDB: connected the application to JawsDB, a MySQL add-on for Heroku.
* Express.js
* MySQL

## End points

Users
https://shrouded-springs-72029.herokuapp.com/api/users  
https://shrouded-springs-72029.herokuapp.com/api/users/:id  
https://shrouded-springs-72029.herokuapp.com/api/users/login  

Posts
https://shrouded-springs-72029.herokuapp.com/api/posts  
https://shrouded-springs-72029.herokuapp.com/api/posts/:id  

Comments
https://shrouded-springs-72029.herokuapp.com/api/comments  
https://shrouded-springs-72029.herokuapp.com/api/comments/:id  

Vote
https://shrouded-springs-72029.herokuapp.com/api/posts/upvote  


