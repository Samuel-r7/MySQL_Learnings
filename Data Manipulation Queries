--Grouping Data:

SELECT department_id, COUNT(*) AS employee_count
FROM employees
GROUP BY department_id;


--Using Aggregate Functions:

SELECT department_id, AVG(salary) AS average_salary
FROM employees
GROUP BY department_id;


-- Ordering Results:

SELECT first_name, last_name, salary
FROM employees
ORDER BY salary DESC;

-- Limiting Results:

SELECT first_name, last_name
FROM employees
LIMIT 5;


--Using Subqueries:

SELECT first_name, last_name
FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);




