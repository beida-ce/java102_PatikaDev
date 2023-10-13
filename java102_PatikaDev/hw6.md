- film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?

        SELECT AVG(rental_rate) FROM film;
        // output: 2.9800000000000000
-------------------
- film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?
       
        SELECT COUNT(*) FROM film 
        WHERE title LIKE 'C%';
        // output: 92
 -------------------
- film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?
        
        SELECT MAX(length) FROM film 
        WHERE rental_rate=0.99;
        // output: 184 
-------------------
- film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?

        SELECT COUNT(distinct replacement_cost) FROM film
        WHERE length > 150 ;
        // output: 21