Let be the number of CITY entries in STATION, and let be the number of distinct CITY names in STATION; query the value of from STATION. In other words, 
find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.

Solution:
/*
Enter your query here.
Please append a semicolon ";" at the end of the query and enter your query in a single line to avoid error.
*/
SELECT COUNT(CITY)-COUNT(DISTINCT CITY) FROM STATION;
