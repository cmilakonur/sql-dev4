# sql-dev4
patika.dev linkim: https://app.patika.dev/cmilakonur <br />

1- film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız. <br />
SELECT  DISTINCT replacement_cost FROM film ;  <br />

2- film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır? <br />
SELECT COUNT( DISTINCT replacement_cost) FROM film ; 21 <br />

3- film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir? <br />
SELECT COUNT( DISTINCT title)  FROM film  WHERE title LIKE 'T%'  and rating='G' ; <br />

4- country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır? <br />
SELECT COUNT(DISTINCT country)  FROM country WHERE country LIKE '_____' ;  <br />

5- city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter? <br />
SELECT COUNT(DISTINCT city) FROM city WHERE city ILIKE '%R' ;  <br />
