# exercise 7:-
## 1.Find the list of all buildings that have employees ✓
```sql
select  distinct building from employees;
```
## 2.Find the list of all buildings and their capacity ✓
```sql
select * from buildings;
```
## 3.List all buildings and the distinct employee roles in each building (including empty buildings) ✓
```sql
SELECT DISTINCT building_name, role 
FROM buildings 
  LEFT JOIN employees
    ON building_name = building;
```