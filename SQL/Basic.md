# Problems

## [Basic Select](https://www.hackerrank.com/domains/sql?filters%5Bsubdomains%5D%5B%5D=select)

### [Revising the Select Query I](https://www.hackerrank.com/challenges/revising-the-select-query)

```sql
-- MySQL
select * from CITY where COUNTRYCODE= "USA" and POPULATION>100000
```

### [Revising the Select Query II](https://www.hackerrank.com/challenges/revising-the-select-query-2)

```sql
-- MySQL
SELECT NAME FROM CITY WHERE POPULATION>120000 AND COUNTRYCODE='USA'
```

### [Revising the Select All](https://www.hackerrank.com/challenges/select-all-sql)

```sql
-- MySQL
SELECT * FROM CITY
```

### [Select By ID](https://www.hackerrank.com/challenges/select-by-id)

```sql
-- MySQL
SELECT * FROM CITY WHERE ID='1661'
```

### [Japanese Cities' Attributes](https://www.hackerrank.com/challenges/japanese-cities-attributes)

```sql
-- MySQL
SELECT * FROM CITY WHERE COUNTRYCODE='JPN'
```

### [Japanese Cities' Names](https://www.hackerrank.com/challenges/japanese-cities-name)

```sql
-- MySQL
SELECT * FROM CITY WHERE COUNTRYCODE='JPN'
```

### [Weather Observation Station 1](https://www.hackerrank.com/challenges/weather-observation-station-1)

```sql
-- MySQL
SELECT CITY, STATE FROM STATION;
```

### [Weather Observation Station 3](https://www.hackerrank.com/challenges/weather-observation-station-3)

```sql
-- MySQL
SELECT DISTINCT(CITY) FROM STATION WHERE ID % 2 = 0
```

> All the other problems revolved using select with conditionals so I'll just skip them from here. Simply coz they don't need any further optimization ¯\_(ツ)\_/¯

## Resources

- [regex101](https://regex101.com/): Test regex patterns
