Hey this is the SQL code, the config.php file might have to be adjusted but everything else should be good.
Here is the SQL code to be pasted into the websites server:

CREATE TABLE users (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    created_at DATETIME DEFAULT CURRENT_TIMESTAMP
);
