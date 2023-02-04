# SQL
Patika SQL ödevler 

--Ödev 8 query 1-test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);

--Ödev 8 query 2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Marje', null, 'mimm0@twitpic.com');
insert into employee (id, name, birthday, email) values (2, 'Udell', '1981-03-21', 'uscoone1@w3.org');
insert into employee (id, name, birthday, email) values (3, 'Joey', '1925-07-09', 'jklaes2@sciencedaily.com');
insert into employee (id, name, birthday, email) values (4, 'Caye', '2003-08-24', 'cbente3@hubpages.com');
insert into employee (id, name, birthday, email) values (5, 'Hedwig', '1934-04-25', null);
insert into employee (id, name, birthday, email) values (6, 'Hildagarde', '1957-12-30', 'hallsebrook5@irs.gov');
insert into employee (id, name, birthday, email) values (7, 'Nealson', '1923-07-04', 'nlerego6@elpais.com');
insert into employee (id, name, birthday, email) values (8, 'Carey', '1996-05-10', null);
insert into employee (id, name, birthday, email) values (9, 'Tracy', '1949-10-29', null);
insert into employee (id, name, birthday, email) values (10, 'Val', '1903-02-28', 'vankrett9@joomla.org');
insert into employee (id, name, birthday, email) values (11, 'Leonelle', '2013-08-12', 'llinaya@trellian.com');
insert into employee (id, name, birthday, email) values (12, 'Gaston', null, 'gloughrenb@telegraph.co.uk');
insert into employee (id, name, birthday, email) values (13, 'Jackelyn', '2010-12-10', null);
insert into employee (id, name, birthday, email) values (14, 'Adaline', '1986-09-25', null);
insert into employee (id, name, birthday, email) values (15, 'Trent', '2007-03-04', null);
insert into employee (id, name, birthday, email) values (16, 'Terrell', '1926-05-20', 'tcarrollf@narod.ru');
insert into employee (id, name, birthday, email) values (17, 'Flo', '1940-06-20', null);
insert into employee (id, name, birthday, email) values (18, 'Beulah', '1929-08-29', null);
insert into employee (id, name, birthday, email) values (19, 'Xaviera', '1962-01-08', 'xstallardi@ed.gov');
insert into employee (id, name, birthday, email) values (20, 'Elinor', null, 'eomoylanej@a8.net');
insert into employee (id, name, birthday, email) values (21, 'Ilyssa', '1952-11-03', null);
insert into employee (id, name, birthday, email) values (22, 'Lorilyn', '1915-08-12', null);
insert into employee (id, name, birthday, email) values (23, 'Starlin', '1957-01-10', 'ssealeafm@dedecms.com');
insert into employee (id, name, birthday, email) values (24, 'Mattie', '2002-07-13', 'mmcilvaneyn@dropbox.com');
insert into employee (id, name, birthday, email) values (25, 'Tore', null, 'twaldockeo@friendfeed.com');
insert into employee (id, name, birthday, email) values (26, 'Milissent', null, 'mrawsthornep@is.gd');
insert into employee (id, name, birthday, email) values (27, 'Fitzgerald', '1987-01-22', 'fascheq@seesaa.net');
insert into employee (id, name, birthday, email) values (28, 'Francklin', '2000-01-24', 'fstricklerr@yellowpages.com');
insert into employee (id, name, birthday, email) values (29, 'Billi', '1911-07-11', null);
insert into employee (id, name, birthday, email) values (30, 'Raymund', '1961-08-31', 'rcobleyt@tamu.edu');
insert into employee (id, name, birthday, email) values (31, 'Kevon', '1924-03-17', null);
insert into employee (id, name, birthday, email) values (32, 'Veronique', '1967-05-17', 'vkimmelv@wikia.com');
insert into employee (id, name, birthday, email) values (33, 'Malena', '1927-04-18', null);
insert into employee (id, name, birthday, email) values (34, 'Boone', '1942-02-03', 'bmilamx@huffingtonpost.com');
insert into employee (id, name, birthday, email) values (35, 'Berte', '1988-11-11', 'bwollersy@squarespace.com');
insert into employee (id, name, birthday, email) values (36, 'Kimberlyn', '1975-04-13', 'kvigarz@symantec.com');
insert into employee (id, name, birthday, email) values (37, 'Dexter', '1932-06-09', 'dleupoldt10@mysql.com');
insert into employee (id, name, birthday, email) values (38, 'Coraline', '1963-03-09', 'cdumphries11@rakuten.co.jp');
insert into employee (id, name, birthday, email) values (39, 'Jessee', '1999-12-23', 'jughi12@si.edu');
insert into employee (id, name, birthday, email) values (40, 'Nanice', '1957-05-24', 'nkingdon13@creativecommons.org');
insert into employee (id, name, birthday, email) values (41, 'Wylie', '2022-12-09', 'wdunnion14@latimes.com');
insert into employee (id, name, birthday, email) values (42, 'Orsa', '1963-03-16', 'osterricks15@nytimes.com');
insert into employee (id, name, birthday, email) values (43, 'Waylan', '1970-03-28', 'weberts16@twitter.com');
insert into employee (id, name, birthday, email) values (44, 'Edmon', null, 'efoxworthy17@squidoo.com');
insert into employee (id, name, birthday, email) values (45, 'Ly', '1929-06-10', 'lkentwell18@privacy.gov.au');
insert into employee (id, name, birthday, email) values (46, 'Kliment', '1947-09-22', 'khamsley19@hp.com');
insert into employee (id, name, birthday, email) values (47, 'Derk', '1959-05-31', null);
insert into employee (id, name, birthday, email) values (48, 'Denyse', '1926-12-27', 'derat1b@wordpress.org');
insert into employee (id, name, birthday, email) values (49, 'Georgine', '2011-07-21', 'gfaraday1c@newsvine.com');
insert into employee (id, name, birthday, email) values (50, 'Rock', '1993-02-18', 'rdonnel1d@google.es');

--Ödev 8 query 3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name = 'Özge',
	birthday = '1996-01-06',
	email = 'ozge@ilhan.com'
WHERE id=16
RETURNING *;

UPDATE employee
SET email = 'hedwig@pais.com'
WHERE name = 'Hedwig'
RETURNING *;

UPDATE employee
SET email = 'd@d.com'
WHERE name LIKE 'D%'
RETURNING *;

UPDATE employee
SET birthday =  '1996-01-06'
WHERE name LIKE '%e'
RETURNING * ;

UPDATE employee
SET name = 'Brown'
WHERE email LIKE 'b%'
RETURNING *;

--Ödev 8 query 4-Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE id = 13 
RETURNING *;

DELETE FROM employee
WHERE name LIKE '%n'
RETURNING *;

DELETE FROM employee
WHERE birthday > '1996-01-06'
RETURNING *;

DELETE FROM employee
WHERE email LIKE '_a%'
RETURNING *;

DELETE FROM employee
WHERE id = 23
RETURNING *;
