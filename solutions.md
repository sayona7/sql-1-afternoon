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


