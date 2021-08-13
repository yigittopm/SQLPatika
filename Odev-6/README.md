### -1 Film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?

```sql
SELECT AVG(rental_rate) FROM film;
```

### 2- Film tablosunda bulunan filmlerden kaçtanesi 'C' karekteri ile başlar?

```sql
SELECT COUNT(*)
FROM film
WHERE title LIKE 'C%';
```
