Create the MySQL database with:

CREATE DATABASE tastybites;
USE tastybites;
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100) UNIQUE,
    password VARCHAR(255)
);

Then run the files on a local server (like XAMPP or WAMP) and use register.html to start.