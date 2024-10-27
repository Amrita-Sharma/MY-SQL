use dog_baby_name

SELECT * from DOG_name_sumy
SELECT * from BABY_NAME_SUMY

 1. Summing the number of names with 'Max' in them

SELECT COUNT(DOG_NAME) FROM DOG_NAME_SUMY
WHERE DOG_NAME LIKE "%MAX%"

2. Summing the number of names that are exactly 'Max'

select COUNT(DOG_NAME) from DOG_name_sumy
WHERE DOG_NAME ="MAX"

3. Checking what the dog names were that contained "Max"

select * from DOG_name_sumy
WHERE DOG_NAME ="MAX"


