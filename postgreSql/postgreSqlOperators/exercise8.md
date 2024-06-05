Select all customers where the country field is NOT one of the the values in the following list:

('Norway', 'Sweden', 'Denmark')
    
    SELECT * FROM customers
    WHERE country NOT IN ('Norway', 'Sweden', 'Denmark');
