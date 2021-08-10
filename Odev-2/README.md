### 1- Film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız)

```sql
SELECT replacement_cost
FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.99;
```

### 2- Actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız)

```sql
SELECT first_name, last_name
FROM actor
WHERE first_name IN('Penelope', 'Nick', 'Ed');
```
