# exercise 16:

## 1.Create a new table named Database with the following columns:
– Name A string (text) describing the name of the database
– Version A number (floating point) of the latest version of this database
– Download_count An integer count of the number of times this database was downloaded
This table has no constraints. ✓

```sql
CREATE TABLE Database (
    Name TEXT,
    Version FLOAT,
    Download_count INTEGER
);
```
```sql #OUTPUT
Name	Version	Download_count
SQLite	3.9	    92000000
MySQL	5.5	    512000000
Postgres 9.4	384000000
```