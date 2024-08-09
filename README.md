# SQL
SQL Portfolio
SELECT MIN(price),item_name
FROM superstore
GROUP BY item_name;

SELECT*
FROM superstore
ORDER BY price;

SELECT max(price),category
FROM superstore
WHERE category='Kitchen Supplies';
