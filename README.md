CREATE DATABASE IF NOT EXISTS battleship;

USE battleship;

CREATE TABLE IF NOT EXISTS accounts
(
    id INT PRIMARY KEY NOT NULL AUTO_INCREMENT,
    log VARCHAR(100),
    pass VARCHAR(100)
);

INSERT INTO accounts VALUES (NULL, 'test', 'test')
