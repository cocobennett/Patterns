# Patterns
Website to format my crochet patterns that are entered into the database

### If access denied for localhost:
In bash, mysql -u root -p

### Creating the Patterns Table
CREATE TABLE patterns (id INT NOT NULL PRIMARY KEY AUTO_INCREMENT, title VARCHAR(255), date TIMESTAMP, images VARCHAR(8000), hook VARCHAR(255), colors VARCHAR(255), weight VARCHAR(255), description VARCHAR(4000), other VARCHAR(4000), rows VARCHAR(8000));
