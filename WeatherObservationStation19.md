SELECT ROUND (SQRT((a - b) * (a - b) + (c - d) * (c - d)), 4) FROM (
SELECT MIN(lat_n) AS a, MAX(lat_n) AS b, MIN(long_w) AS c, MAX(long_w) AS d FROM station);
