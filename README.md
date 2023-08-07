# Sign-Up-Page-Using-PHP
Sign up and login page using PHP and MySQL

Create a Table users in the database 
 CREATE TABLE users (
    ->     id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    ->     username VARCHAR(50) NOT NULL UNIQUE,
    ->     password VARCHAR(255) NOT NULL,
    ->     created_at DATETIME DEFAULT CURRENT_TIMESTAMP
    -> );
