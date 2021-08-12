### 1- Country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız

```sql
SELECT * 
FROM country
WHERE country LIKE 'A%a';
```