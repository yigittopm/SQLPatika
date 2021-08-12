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

### 3- Film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?

```sql
SELECT COUNT(*)
FROM film
WHERE title LIKE 'T%' AND rating='G';
```

### 4- Country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?

```sql
SELECT COUNT(*)
FROM country
WHERE LENGTH(country) = 5;
```
