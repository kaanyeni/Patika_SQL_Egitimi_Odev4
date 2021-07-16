# Patika_SQL_Egitimi_Odev4
1. Soru: film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
+ ` select distinct replacement_cost from film `
2. film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
+ ` select count (distinct replacement_cost) from film'`
3. Soru: film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
+ ` select count (*) from film where title like ('T%') and rating='G'`
4. Soru: country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
+ `select count (*) from country where length(country)= 5  `
5. Soru: city tablosundaki şehir isimlerinin kaçtanesi 'R' veya r karakteri ile biter?
+ ` select count(*) from city where city ilike('%r')  `
