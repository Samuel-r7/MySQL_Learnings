CREATE DATABASE my_database;

--Table creation:

CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    email VARCHAR(100),
    salary DECIMAL(10, 2),
    hire_date DATE
);

-- Inserting Data into a Table:

INSERT INTO employees (first_name, last_name, email, salary, hire_date)
VALUES ('John', 'Doe', 'john.doe@example.com', 50000.00, '2024-08-19');

--Selecting Data from a Table:

SELECT first_name, last_name, salary
FROM employees
WHERE salary > 40000;

--Updating Data in a Table:

UPDATE employees
SET salary = 55000.00
WHERE id = 1;

--Deleting Data from a Table:

DELETE FROM employees
WHERE id = 1;
