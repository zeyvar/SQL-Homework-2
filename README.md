# SQL-Homework-2
BETWEEN IN Ödev 2
---
--SORU 1
SELECT * from film
where replacement_cost BETWEEN 12.99 AND 16.99;

-- SORU 2
SELECT first_name, last_name from actor WHERE first_name IN ('Penelope', 'Ed') 

--SORU 3
select * from film 
where rental_rate IN(0.99,2.99,4.99) AND replacement_cost IN (12.99,15.99,28.99
