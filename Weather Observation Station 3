Problem:Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.
The STATION table is described as follows:
ID,STATE,CITY,LAT_N,LONG_W

Intial Analysis:
From table: STATION
Where: ID = even number, Exclude duplicates
Select: City 

Operator used: mod(field,num) 

Solution:
SELECT DISTINCT CITY FROM STATION where mod(ID,2)=0 ;
