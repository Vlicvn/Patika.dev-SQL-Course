
# Patika.dev - SQL 


1. film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.
```sql
SELECT title, rating FROM film
GROUP BY title, rating;
```

2. film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.
```sql
SELECT replacement_cost, COUNT(*) AS film_count
FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50
ORDER BY replacement_cost;
```

3. customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir?
```sql
SELECT store_id, COUNT(*) AS customer_count
FROM customer
GROUP BY store_id;
```

4. city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.
```sql
SELECT country_id, COUNT(*) AS city_count
FROM city
GROUP BY country_id
ORDER BY city_count DESC
LIMIT 1;
```


[Patika.dev - SQL kursuna gitmek için tıklayın.](https://academy.patika.dev/tr/courses/sql)
