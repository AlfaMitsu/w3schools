Choose the correct JOIN clause to select all records from the two tables where there is a match in both tables.

    SELECT *
    FROM Orders
    INNER JOIN Customers
    ON Orders.CustomerID=Customers.CustomerID;
