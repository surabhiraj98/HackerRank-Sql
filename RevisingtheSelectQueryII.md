Query the names of all American cities in CITY with populations larger than 120000. The CountryCode for America is USA. 

Solution:
SELECT NAME FROM CITY WHERE COUNTRYCODE = 'USA' AND POPULATION > 120000;
