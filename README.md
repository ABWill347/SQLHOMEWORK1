# SQLHOMEWORK1

SQL JOINs are used to combine rows from two or more tables, based on a related column between them. There are several types of JOINs:

INNER JOIN: Returns rows when there is a match in both tables.
Syntax: SELECT * FROM table1 INNER JOIN table2 ON table1.column_name = table2.column_name;
Example: If you want to show book titles along with their authors, you would join the books table with the authors table where the author_id matches.


LEFT JOIN (or LEFT OUTER JOIN): Returns all rows from the left table, and the matched rows from the right table. If there are no matches, the result is NULL on the right side.
Syntax: SELECT * FROM table1 LEFT JOIN table2 ON table1.column_name = table2.column_name;
Example: To display all books, including those without authors, you would LEFT JOIN the books table with the authors table.


RIGHT JOIN (or RIGHT OUTER JOIN): Returns all rows from the right table, and the matched rows from the left table. If there are no matches, the result is NULL on the left side.
Syntax: SELECT * FROM table1 RIGHT JOIN table2 ON table1.column_name = table2.column_name;
Example: To display all authors, including those without books, you would RIGHT JOIN the authors table with the books table.


FULL JOIN (or FULL OUTER JOIN): Returns rows when there is a match in one of the tables. It combines the results of both LEFT and RIGHT JOINs.
Syntax: SELECT * FROM table1 FULL OUTER JOIN table2 ON table1.column_name = table2.column_name;
Example: To show all books and all authors, regardless of whether they are matched or not, you would use a FULL JOIN between books and authors.






