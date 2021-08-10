### 1- Film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.

```sql
SELECT title, description FROM film; 
```

### 2- Film tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.

```sql
SELECT * 
FROM film
WHERE length > 60 AND length < 75;
```

### 3- Film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99 VE replacement_cost 12.99 VEYA 28.99 olma koşullarıyla sıralayınız.

```sql
SELECT *
FROM film
WHERE rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99);
```