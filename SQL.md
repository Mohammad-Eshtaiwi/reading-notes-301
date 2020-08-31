# SQL

SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

relational database :is a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

```

SELECT column, another_column, …
FROM mytable;
WHERE condition
    AND/OR another_condition
    AND/OR …;
```

-   SELECT used to select columns to show

-   FROM used to select the table that we want to get the data from

-   WHERE condition used to add conditions to the query
-   DISTINCT used at the select statment to show only the unique data

```
INSERT INTO boxoffice
(movie_id, rating, sales_in_millions)
VALUES (1, 9.9, 283742034 / 1000000);
```

insert new record into boxoffice

```
UPDATE mytable
SET column = value_or_expr,
    other_column = another_value_or_expr,
    …
WHERE condition;
```

update The records which pass the condition

```
DELETE FROM mytable
WHERE condition;

```

delete The records which pass the condition
