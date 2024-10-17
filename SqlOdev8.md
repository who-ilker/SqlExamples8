1)test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```sql
CREATE TABLE employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100) NOT NULL
);
```

2)Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```sql
insert into employee (id, name, birthday, email) values (3, 'Chuck', '1971-05-21', 'csoutherns2@netlog.com');
insert into employee (id, name, birthday, email) values (4, 'Justina', '1978-05-26', 'jbosward3@un.org');
insert into employee (id, name, birthday, email) values (5, 'Nollie', '2000-08-16', 'ncheine4@illinois.edu');
insert into employee (id, name, birthday, email) values (6, 'Elnora', null, 'eingleby5@sphinn.com');
insert into employee (id, name, birthday, email) values (7, 'Addia', null, 'alush6@wikipedia.org');
insert into employee (id, name, birthday, email) values (8, 'Aurelie', '1959-10-03', 'alesaunier7@reuters.com');
insert into employee (id, name, birthday, email) values (9, 'Ravid', '1965-01-07', 'rubanks8@ustream.tv');
insert into employee (id, name, birthday, email) values (10, 'Brit', '2023-08-02', 'bcuerdale9@home.pl');
insert into employee (id, name, birthday, email) values (11, 'Moe', '1918-07-09', 'mtarpeya@topsy.com');
insert into employee (id, name, birthday, email) values (12, 'Willetta', null, 'wmacknishb@scribd.com');
insert into employee (id, name, birthday, email) values (13, 'Lyda', '1990-07-11', 'lpimblottec@smh.com.au');
insert into employee (id, name, birthday, email) values (14, 'Melinde', null, 'mkieransd@theguardian.com');
insert into employee (id, name, birthday, email) values (15, 'Nicki', '1920-12-12', 'nlejeunee@oracle.com');
insert into employee (id, name, birthday, email) values (16, 'Dareen', '1943-09-12', 'delstonef@constantcontact.com');
insert into employee (id, name, birthday, email) values (17, 'Basil', '2021-02-02', 'bmatschekg@cnbc.com');
insert into employee (id, name, birthday, email) values (18, 'Clay', '1928-10-17', 'csatcherh@prweb.com');
insert into employee (id, name, birthday, email) values (19, 'Ashlin', '1929-12-14', 'arobeiroi@fema.gov');
insert into employee (id, name, birthday, email) values (20, 'Kathy', '1950-08-21', 'khawkj@scientificamerican.com');
insert into employee (id, name, birthday, email) values (21, 'Uta', null, 'ustickfordk@about.me');
insert into employee (id, name, birthday, email) values (22, 'Marrissa', '2017-06-06', 'mmummeryl@mozilla.com');
insert into employee (id, name, birthday, email) values (23, 'Phyllida', null, 'pcaseleym@google.co.jp');
insert into employee (id, name, birthday, email) values (24, 'Rocky', '1958-07-07', 'rwingattn@ezinearticles.com');
insert into employee (id, name, birthday, email) values (25, 'Bo', '1922-09-27', 'bprioro@netlog.com');
insert into employee (id, name, birthday, email) values (26, 'Craggy', '1943-10-22', 'cnewrickp@etsy.com');
insert into employee (id, name, birthday, email) values (27, 'Ardella', '1929-12-09', 'ajuraq@wired.com');
insert into employee (id, name, birthday, email) values (28, 'Donalt', '1974-01-24', 'dmacvayr@vimeo.com');
insert into employee (id, name, birthday, email) values (29, 'Evangelia', '1921-08-04', 'eflattes@skype.com');
insert into employee (id, name, birthday, email) values (30, 'Price', '1995-06-18', 'psearchwellt@cbsnews.com');
insert into employee (id, name, birthday, email) values (31, 'Anita', '1940-01-05', 'ablackborou@indiegogo.com');
insert into employee (id, name, birthday, email) values (32, 'Reinald', '2014-06-10', 'radamowiczv@shareasale.com');
insert into employee (id, name, birthday, email) values (33, 'Madel', '1995-11-06', 'memanulssonw@livejournal.com');
insert into employee (id, name, birthday, email) values (34, 'Lammond', '2022-04-25', 'ldebellisx@wufoo.com');
insert into employee (id, name, birthday, email) values (35, 'Allyson', '1900-12-04', 'acastelluzziy@huffingtonpost.com');
insert into employee (id, name, birthday, email) values (36, 'Gabbey', '1987-09-27', 'gpoppyz@paypal.com');
insert into employee (id, name, birthday, email) values (37, 'Franklyn', '1944-03-13', 'fmarchment10@zimbio.com');
insert into employee (id, name, birthday, email) values (38, 'Kinny', '1960-04-07', 'kburnhams11@yandex.ru');
insert into employee (id, name, birthday, email) values (39, 'Claudine', '1961-04-19', 'cbowyer12@microsoft.com');
insert into employee (id, name, birthday, email) values (40, 'Harley', '1927-02-04', 'hdallimare13@tumblr.com');
insert into employee (id, name, birthday, email) values (41, 'Lou', '2022-08-30', 'lleate14@webeden.co.uk');
insert into employee (id, name, birthday, email) values (42, 'Camey', '1900-12-06', 'ceskriett15@g.co');
insert into employee (id, name, birthday, email) values (43, 'Flynn', '1936-07-13', 'feick16@imageshack.us');
insert into employee (id, name, birthday, email) values (44, 'Fayina', '1972-05-04', 'frhyme17@sitemeter.com');
insert into employee (id, name, birthday, email) values (45, 'Hollis', '2005-10-12', 'hbrooks18@theatlantic.com');
insert into employee (id, name, birthday, email) values (46, 'Kimbell', '1957-06-25', 'kprimrose19@mtv.com');
insert into employee (id, name, birthday, email) values (47, 'Enrique', '2007-02-28', 'ehassur1a@adobe.com');
insert into employee (id, name, birthday, email) values (48, 'Bernete', '2003-10-18', 'bjados1b@google.de');
insert into employee (id, name, birthday, email) values (49, 'Tawsha', '1940-10-31', 'thodgets1c@google.co.uk');
insert into employee (id, name, birthday, email) values (50, 'Cora', '2021-02-07', 'cmarshland1d@ycombinator.com');
```

3)Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
UPDATE employee
SET name = 'Ilker', birthday = '1950-12-31'
WHERE name = 'İlker';

UPDATE employee
SET birthday = '2024-01-01'
WHERE birthday IS NULL;

UPDATE employee
SET email = REPLACE(email, '.com', '.old')
WHERE birthday < '2000-01-01';

UPDATE employee
SET email = CONCAT(email, '.tr')
WHERE email LIKE '%.com';

UPDATE employee
SET name = CONCAT (name, ' (GENZ)')
WHERE birthday > '2020-01-01';
```

4)Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee
WHERE name = 'Ilker' AND id = '1';

DELETE FROM employee
WHERE birthday is NULL;

DELETE FROM employee
WHERE birthday > '2020-01-01';

DELETE FROM tablo
WHERE email LIKE '%@gmail.com';

DELETE FROM tablo
WHERE id > 40;
```