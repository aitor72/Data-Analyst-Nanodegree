## P1 - Exploring Weather Trends

select * from city_data where city in (select city from city_list where city in( 'Barcelona' ))
and country in ( select country from city_list where country = 'Spain')



select * from global_data



