Problem:Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name). 
If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.

Initial Analysis:
For shortest city 
From : STATION
Order by: char_length(City) asc
select: top 1


For longest city 
From : STATION
Order by: char_length(City) desc
select: top 1

select TOP 1 CITY,LEN(CITY) FROM STATION ORDER BY LEN(CITY) ASC,CITY ASC
select TOP 1 CITY,LEN(CITY) FROM STATION ORDER BY LEN(CITY) DESC,CITY ASC

