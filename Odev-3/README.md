### 1- Country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız

```sql
SELECT * 
FROM country
WHERE country LIKE 'A%a';
```

### 2- Country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız

```sql
SELECT * 
FROM country
WHERE LENGTH(country) > 5 AND country LIKE '%n';
```

### 3- Film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız

```sql
SELECT title
FROM film
WHERE title ILIKE '%T%T%T%T%';
```
