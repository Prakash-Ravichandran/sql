# sql

## CREATING A TABLE

```sql

CREATE TABLE dogs (
   name VARCHAR(50),
   age INT
)

```

## How do we know the row/columns affected ?

```sql

SHOW COLUMNS FROM <tablename>

(or)

DESC <tablename>
```

## Drop tables

```sql

DROP TABLE <table-name>;

DROP TABLE cats;

```

## Exercise - create table pastries

```sql
CREATE TABLE pastries ( name VARCHAR(50), quantity INT);
```
