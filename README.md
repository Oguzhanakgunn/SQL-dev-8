# SQL-dev-8
https://app.patika.dev/courses/sql/Odev8


1) test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);


2) Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.



--insert into employee (name, birthday, email) values ('Stacy', '2015-10-24', 'sianitti0@symantec.com');
--insert into employee (name, birthday, email) values ('Harri', '1970-01-12', 'hsunock1@typepad.com');
--insert into employee (name, birthday, email) values ('Homer', null, 'hlickess2@chron.com');
--insert into employee (name, birthday, email) values ('Murial', '1921-06-02', 'mdobbyn3@theguardian.com');
--insert into employee (name, birthday, email) values ('Andrew', '1961-09-28', 'aniche4@wsj.com');
--insert into employee (name, birthday, email) values ('Brad', '1984-01-08', 'blacky5@godaddy.com');
--insert into employee (name, birthday, email) values ('Chauncey', null, 'cwalby6@php.net');
--insert into employee (name, birthday, email) values ('Karine', '1950-09-28', 'kbattye7@ucoz.ru');
--insert into employee (name, birthday, email) values ('Silvio', '1947-11-30', 'siskower8@sciencedaily.com');
--insert into employee (name, birthday, email) values ('Cobb', '1911-10-23', 'cmanuele9@pbs.org');
--insert into employee (name, birthday, email) values ('Celesta', null, 'cmegarrella@google.ru');
--insert into employee (name, birthday, email) values ('Torr', '1939-05-16', 'tludlemb@answers.com');
--insert into employee (name, birthday, email) values ('Beth', '2016-03-25', 'bphlippic@flavors.me');
--insert into employee (name, birthday, email) values ('Franz', '1945-05-22', 'fschabend@wordpress.com');
--insert into employee (name, birthday, email) values ('Halli', '1949-08-20', 'hpadricke@ustream.tv');
--insert into employee (name, birthday, email) values ('Vernon', '1988-09-21', 'vgasconef@wiley.com');
--insert into employee (name, birthday, email) values ('Dolorita', '2016-03-17', 'dgilleong@discovery.com');
--insert into employee (name, birthday, email) values ('Annabel', '1996-12-10', 'adelbergueh@delicious.com');
--insert into employee (name, birthday, email) values ('Lonni', '1969-08-12', 'lkeymeri@themeforest.net');
--insert into employee (name, birthday, email) values ('Ryley', null, 'rrysdalej@census.gov');
--insert into employee (name, birthday, email) values ('Ingram', '2006-08-01', 'igoldenk@aboutads.info');
--insert into employee (name, birthday, email) values ('Brose', null, 'bjeanenetl@smh.com.au');
--insert into employee (name, birthday, email) values ('Fred', '1935-03-26', 'fquerreem@hibu.com');
--insert into employee (name, birthday, email) values ('Frederich', '1962-08-15', 'fjudkinsn@bandcamp.com');
--insert into employee (name, birthday, email) values ('Robbyn', '1953-12-17', 'rpetrolo@gizmodo.com');
--insert into employee (name, birthday, email) values ('Lianne', '1964-10-04', 'lgabrielip@comcast.net');
--insert into employee (name, birthday, email) values ('Haze', '1964-11-13', 'holdfieldcherryq@csmonitor.com');
--insert into employee (name, birthday, email) values ('Carson', null, 'cpendrickr@unc.edu');
--insert into employee (name, birthday, email) values ('Kain', null, 'kbeinings@surveymonkey.com');
--insert into employee (name, birthday, email) values ('Maridel', '1934-09-04', 'mfretwellt@cnet.com');
--insert into employee (name, birthday, email) values ('Frederick', '1972-10-10', 'fbovingdonu@deviantart.com');
--insert into employee (name, birthday, email) values ('Matilda', '1908-02-08', 'mgreatorexv@topsy.com');
--insert into employee (name, birthday, email) values ('Mead', '1997-04-12', 'mraggw@cyberchimps.com');
--insert into employee (name, birthday, email) values ('Iolanthe', '1912-01-18', 'idibsonx@umn.edu');
--insert into employee (name, birthday, email) values ('Malanie', '1980-05-11', 'mlenniey@studiopress.com');
--insert into employee (name, birthday, email) values ('Scarlett', '2005-08-20', 'sduvalz@seesaa.net');
--insert into employee (name, birthday, email) values ('Kimberley', '1928-12-11', 'kmccuis10@unblog.fr');
--insert into employee (name, birthday, email) values ('Beverlie', '2019-07-14', 'bbiddlestone11@who.int');
--insert into employee (name, birthday, email) values ('Nara', '1994-05-24', 'nflaunders12@fotki.com');
--insert into employee (name, birthday, email) values ('Lind', '1999-12-19', 'lithell13@de.vu');
--insert into employee (name, birthday, email) values ('Cosimo', '1959-04-08', 'cstraker14@yelp.com');
--insert into employee (name, birthday, email) values ('Alfreda', null, 'abucktrout15@soundcloud.com');
--insert into employee (name, birthday, email) values ('Prinz', '1985-02-06', 'pbruinemann16@blinklist.com');
--insert into employee (name, birthday, email) values ('Blancha', '1905-12-27', 'bcopo17@reverbnation.com');
--insert into employee (name, birthday, email) values ('Katina', '1941-05-01', 'kharral18@miitbeian.gov.cn');
--insert into employee (name, birthday, email) values ('Roze', '1929-04-24', 'rsolon19@businessinsider.com');
--insert into employee (name, birthday, email) values ('Dionisio', '1903-03-02', 'dcrinage1a@bigcartel.com');
--insert into employee (name, birthday, email) values ('Donaugh', '2003-09-15', 'dkoppen1b@tuttocitta.it');
--insert into employee (name, birthday, email) values ('Lief', '2010-05-15', 'letchingham1c@flavors.me');
--insert into employee (name, birthday, email) values ('Jessalyn', '1906-09-18', 'jgyngyll1d@diigo.com');

3) Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name = 'İsmail'
WHERE name LIKE 'R%'
RETURNING *;

UPDATE employee
SET name = 'ABC'
WHERE id = 8
RETURNING *;

UPDATE employee
SET email = NULL
WHERE id >45
RETURNING *;

UPDATE employee
SET name = 'XXX'
WHERE birthday = '1906-09-18'
RETURNING *;

UPDATE employee
SET birthday = NULL
WHERE name LIKE 'M%l'
RETURNING *;

4) Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE email LIKE 't%'
RETURNING *;

DELETE FROM employee
WHERE id > 30
RETURNING *;

DELETE FROM employee
WHERE birthday IS NULL
RETURNING *;

DELETE FROM employee
WHERE name = 'İsmail'
RETURNING *;

DELETE FROM employee 
WHERE  birthday >= '2000-01-01'
AND birthday <= '2022-01-01'
RETURNING *;
