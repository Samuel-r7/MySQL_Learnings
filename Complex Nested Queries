--This query uses a subquery to calculate the average salary for each department
--and compares each employee's salary against that average.

--Find Employees with Salaries Higher Than the Average Salary in Their Department

SELECT first_name, last_name, salary
FROM employees e
WHERE salary > (
    SELECT AVG(salary)
    FROM employees
    WHERE department_id = e.department_id
);
