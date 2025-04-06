Hi There, 

 your welcom here...!!

This is mini project hosted in docker, here i've used 
Project Highlights:
🔹 hashtag#Frontend: Clean UI served via Nginx
 🔹 hashtag#Backend: Flask (Python), powering RESTful APIs
 🔹 hashtag#Database: MySQL – fully containerized
 🔹 hashtag#Orchestration: All services are connected and running with docker-compose
All of them are containerized using Docker and orchestrated together using Docker Compose.

#Commands used:

Docker-compose commands 

> docker-compose up
> docker-compose down
> docker exec -it <docker container id> bash
> docker logs <container id>
> docker ps -a
> docker-compose build
> docker container ls
> docker exec -it miniproject-db-1 mysql -u root -p {Login to mysql conatiner}
> docker exec -it miniproject-db-1 mysql -uroot -prootpassword


!!---------- MYSQL -------------------------------!!

SHOW DATABASES;
USE mydb;
SHOW TABLES;


Create a TABLE:

CREATE TABLE users (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    location VARCHAR(100),
    lastworkingdate Date
);


To view Table data:

SELECT * FROM users;


Delete a column in table:

ALTER TABLE users DROP COLUMN age;


To view all table list:

SHOW TABLES;


Add a new id and details:

ALTER TABLE users ADD COLUMN lastworkingdate DATE;

Aadd new row in table:

INSERT INTO users (id, name, age, location, lastworkingdate)
VALUES (201300, 'B SURYA PRAKASH REDDY', 28, 'TCS-HYDERABAD', '2025-04-01');

Display table data with ID:

SELECT * FROM users WHERE id = 201300;

Delete ID in table:

DELETE FROM users WHERE id=201300;

To update an existing user:

INSERT INTO users (id, name, age, place, lastworkingdate)
VALUES (26, 'B SURYA PRAKASH REDDY', 30, 'Bangalore', '2025-04-06');

Delete a Column in a Table:

ALTER TABLE users DROP COLUMN age;










