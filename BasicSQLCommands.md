##### Create a table
```
CREATE TABLE friends (
   id INTEGER,
   name TEXT,
   birthday DATE
);
````

##### Example: 

```
CREATE TABLE friends (
    id INTEGER,
    name TEXT,
    birthday DATE,
);
```
-----------------------------
##### Insert Into Table
```
INSERT INTO table_name (column1, column2, column3) 
VALUES (value1, value2, value3);
```

##### Example: 

```
INSERT INTO friends (id, name, birthday)
VALUES (1, 'Jane Doe', '1990-05-30')
```
------------------------------

##### Check that object has been added to the database:
```
SELECT * 
FROM friends;
```
