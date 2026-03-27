# experiment 4
## List all directors of Pixar movies (alphabetically), without duplicates ✓
```
SELECT director FROM movies
group by director;
```
## List the last four Pixar movies released (ordered from most recent to least) ✓
```
SELECT*from movies
order by year desc
limit 4;
```
## List the first five Pixar movies sorted alphabetically ✓
```
SELECT*from movies
order by title asc
limit 5;
```
## List the next five Pixar movies sorted alphabetically ✓
```
SELECT*from movies
order by title asc
limit 5
offset 5;
```
---