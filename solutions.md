-- Table - person
-- 1.
-- create table person (
-- 	person_id serial,
--   name varchar(50),
--   age integer,
--   height_cm integer,
--   city varchar(100),
--   favorite_color varchar(25)
-- );

-- 2.
-- insert into person (
-- 	name,
--   age,
--   height_cm,
--   city,
--   favorite_color
-- ) values (
-- 	'Joe',
--   20,
--   175,
--   'Lehi',
--   'blue'
-- );

-- insert into person (
-- 	name,
--   age,
--   height_cm,
--   city,
--   favorite_color
-- ) values (
-- 	'Anna',
--   25,
--   165,
--   'Austin',
--   'black'
-- );

-- insert into person (
-- 	name,
--   age,
--   height_cm,
--   city,
--   favorite_color
-- ) values (
-- 	'Diego',
--   30,
--   180,
--   'San Antonio',
--   'grey'
-- );

-- insert into person (
-- 	name,
--   age,
--   height_cm,
--   city,
--   favorite_color
-- ) values (
-- 	'Lara',
--   10,
--   125,
--   'Houston',
--   'lilac'
-- );

-- insert into person (
-- 	name,
--   age,
--   height_cm,
--   city,
--   favorite_color
-- ) values (
-- 	'Meggie',
--   67,
--   160,
--   'Boston',
--   'white'
-- );

-- 3.
-- select * from person
-- order by height_cm desc;

-- 4.
-- select * from person
-- order by height_cm asc;

-- 5.
-- select * from person
-- order by age desc;

-- 6.
-- select * from person
-- where age > 20;

-- 7.
-- select * from person
-- where age = 18;

-- 8.
-- select * from person
-- where age < 20 or age > 30;

-- 9. 
-- select * from person
-- where age != 27;

-- 10. 
-- select * from person
-- where favorite_color != 'red';

-- 11. 
-- select * from person
-- where favorite_color != 'red' and favorite_color != 'blue';

-- 12.
-- select * from person
-- where favorite_color = 'orange' or favorite_color = 'green';

-- 13. 
-- select * from person
-- where favorite_color in ('orange', 'green', 'blue');

-- 14.
-- select * from person
-- where favorite_color in ('yellow', 'purple');


-- Table - orders:

-- 1.
-- create table orders (
-- 	order_id serial,
--   person_id integer,
--   product_name varchar(100),
--   product_price decimal,
--   quantity integer
-- );

-- 2. 
-- insert into orders (
--   person_id,
--   product_name,
--   product_price,
--   quantity
-- ) values (
-- 	1,
--   'lipstick',
--   9.50,
--   2
-- );

-- insert into orders (
--   person_id,
--   product_name,
--   product_price,
--   quantity
-- ) values (
-- 	2,
--   'shampoo',
--   8.00,
--   1
-- );

-- insert into orders (
--   person_id,
--   product_name,
--   product_price,
--   quantity
-- ) values (
-- 	2,
--   'conditioner',
--   8.50,
--   1
-- );

-- insert into orders (
--   person_id,
--   product_name,
--   product_price,
--   quantity
-- ) values (
-- 	3,
--   'perfume',
--   25.00,
--   1
-- );

-- insert into orders (
--   person_id,
--   product_name,
--   product_price,
--   quantity
-- ) values (
-- 	4,
--   'cotton balls',
--   11.00,
--   3
-- );

-- 3.
-- select sum(quantity)
-- from orders;

-- 4. 
-- select sum(product_price * quantity)
-- from orders;

-- 5. 
-- select sum(product_price * quantity)
-- from orders
-- where person_id = 2;



-- Table - artists
-- 1.
-- insert into artist (name)
-- values ('Sia');

-- insert into artist (name)
-- values ('Halsey');

-- insert into artist (name)
-- values ('Alessia Cara');

-- 2.
-- select * from artist
-- order by name desc limit 10;

-- 3.
-- select * from artist
-- order by name asc limit 5;

-- 4.
-- select * from artist
-- where name like 'Black% ';

-- 5.
-- select * from artist
-- where name like '%Black%';


-- Table - employee

-- 1.
-- select first_name, last_name
-- from employee
-- where city = 'Calgary';

-- 2.
-- select max(birth_date) from employee;

-- 3.
-- select min(birth_date) from employee;

-- 4. 
-- select * from employee
-- where reports_to = 2;

-- 5.
-- select count(*)
-- from employee
-- where city = 'Lethbridge';


