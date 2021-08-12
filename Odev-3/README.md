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