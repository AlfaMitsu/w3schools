Select all customers where the customer_name field contains at least one 'a' character.

Hint: Use the % wildcard.

    SELECT * FROM customers
    WHERE customer_name LIKE '%a%';
