Insert the missing parts in the JOIN clause to join the two tables orders and customers, using the customer_id field in both tables as the relationship between the two tables.

    SELECT * FROM orders
    LEFT JOIN customers
    ON orders.customer_id = customers.customer_id;
