Select all customers where the country field is one of the the values in the following list:

('Norway', 'Sweden', 'Denmark')

    SELECT * FROM customers
    WHERE country IN ('Norway', 'Sweden', 'Denmark');
