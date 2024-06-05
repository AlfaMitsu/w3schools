List the number of customers in each country.

    SELECT COUNT(customer_id) AS Number_of_Customers, country
    FROM customers
    GROUP BY country;
