# MySQL-Assignment-2-Querying-Data

PROCEDURE 
   * Distinct Remove duplicate  salary values.
   * AS Employee_Age renames the Age column in the output.
     AS Employee_Salary renames the Salary column in the output.
   * Salary > 50000 selects employees earning more than ₹50,000.
     HireDate < '2016-01-01' selects employees hired before January 1, 2016.
   * ASC (ascending) is optional because it is the default sort order, but it is included here for clarity
   * YEAR(HireDate) = 2018 filters employees hired in the year 2018.
     ORDER BY HireDate ASC sorts them from the earliest hire date to the latest.
     LIMIT 5 returns only the first 5 employees..
   * using aggregate function Returns the total salary paid to employees in the Finance department.
   * GROUP BY Location groups employees by location.
     MAX(Salary) returns the highest salary in each location.
   * GROUP BY Department groups employees by department.
     COUNT(*) counts the number of employees in each department.
     HAVING COUNT(*) < 3 filters the groups to show only departments with fewer than 3 employees.
    *INNER JOIN returns only records that have matching values in both tables.
    *LEFT JOIN returns all departments from the Departments table
    *RIGHT JOIN returns all records from the Locations table.  
