Choose the correct JOIN clause to select all the records from the customers table plus all the matches in the orders table.

    SELECT * FROM customers
    RIGHT JOIN orders
    ON customers.customer_id = orders.customer_id;
