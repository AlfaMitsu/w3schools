Choose the correct JOIN clause to select all records from the two tables where there is a match in both tables.

    SELECT * FROM orders
    INNER JOIN customers
    ON orders.customer_id = customers.customer_id;
