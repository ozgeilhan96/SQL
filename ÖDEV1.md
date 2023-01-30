# SQL
Patika SQL ödevler 
--Ödev 1 query 1
select title , description from film;
--Ödev 1 query 2
select * from film
where length > 60 and length < 75 ;
--Ödev 1 query 3
select * from film 
where rental_rate = 0.99 and replacement_cost = 12.99 or replacement_cost = 28.99;
--Ödev 1 quey 4
select first_name , last_name from customer
where first_name = 'Mary';
--Ödev 1 query 5
select * from film
where (not (length>50)) and not (rental_rate = 2.99 or rental_rate =4.99);
