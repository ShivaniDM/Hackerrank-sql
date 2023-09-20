## Problem Statement:
> Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.

The CITY table is described as follows:</br>
`field: ID,NAME, COUNTRYCODE, DISTRICT, POPULATION`

## Initial Analysis:
- Table from which details are being fetched: `CITY`
- Condition applicable: Population and Countrycode
- Select : all fields from the table `CITY`

## Solution:
```sql
/* from : CITY ,  condition: population>100000 AND COUNTRYCODE == 'USA' , column required: all (*) */
SELECT *FROM CITY WHERE POPULATION >100000 AND COUNTRYCODE = 'USA';
```
