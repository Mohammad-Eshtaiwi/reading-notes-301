# Normalization

the main goal of the normalization is to organize and simplify the database tables to reduce the complixty and the duplication of the data and make the tables have only one purpose.

## Resons Of Normalization:

-   minimize duplicate data

-   minimize or avoid data modification issues

-   simplify queries

## Duplicated information presents two problems:

-   It increases storage and decrease performance.
-   It becomes more difficult to maintain data changes.

## Normalization Forms

-   First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
-   Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
-   Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key
