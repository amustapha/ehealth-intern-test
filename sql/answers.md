# Task 4

1. Based on naming convention, the query seems to return a list of
   all people from the runner table where the person runner hasn't won any race.

2. The query would return 50 records. For each of the records of the 
    Dept table, it returns all the records of Emp table with a Union operator. 

3. `UPDATE SALARIES SET Sex=IF(Sex="m", "f", "m");`
4. The query would return all customers who were not referred by user 
   id 2. An efficient way to write such query would be 
   `SELECT Name FROM Customers WHERE NOT ReferredBy = 2`