### 1- Film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız

```sql
SELECT DISTINCT replacement_cost
FROM film;
```

### 2- Film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?

```sql
SELECT COUNT(DISTINCT replacement_cost)
FROM film;
```
