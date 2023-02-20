- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
 
```SQL
CREATE TABLE employee (
id SERIAL PRIMARY KEY,
name VARCHAR(50) NOT NULL,
email VARCHAR(100),
birthday DATE
);
```


- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```SQL
insert into employee (id, name, email, birthday) values (1, 'Felita', 'fmochar0@walmart.com', '2022-11-03');
insert into employee (id, name, email, birthday) values (2, 'Barney', 'bgaskamp1@flickr.com', '2022-10-17');
insert into employee (id, name, email, birthday) values (3, 'Mag', 'mshiel2@dot.gov', '2022-10-31');
insert into employee (id, name, email, birthday) values (4, 'Carlo', 'cdayborne3@hud.gov', '2022-03-27');
insert into employee (id, name, email, birthday) values (5, 'Gretna', 'gtrunkfield4@linkedin.com', '2022-04-19');
insert into employee (id, name, email, birthday) values (6, 'Doloritas', 'dcastelletto5@hhs.gov', '2022-03-23');
insert into employee (id, name, email, birthday) values (7, 'Britni', 'bbeardwell6@cocolog-nifty.com', '2022-08-19');
insert into employee (id, name, email, birthday) values (8, 'Gilli', 'gmackeller7@mac.com', '2022-09-09');
insert into employee (id, name, email, birthday) values (9, 'Shurlocke', 'sdulson8@trellian.com', '2023-01-07');
insert into employee (id, name, email, birthday) values (10, 'Mildrid', 'mleban9@discovery.com', '2022-12-18');
insert into employee (id, name, email, birthday) values (11, 'Adelind', 'aagenta@salon.com', '2022-11-27');
insert into employee (id, name, email, birthday) values (12, 'Kacie', 'khelmkeb@sciencedirect.com', '2022-07-28');
insert into employee (id, name, email, birthday) values (13, 'Hyacinth', 'hiannellic@comcast.net', '2022-09-02');
insert into employee (id, name, email, birthday) values (14, 'Henriette', 'hblacklawed@homestead.com', '2022-04-19');
insert into employee (id, name, email, birthday) values (15, 'Kaylil', 'kwinchurste@hhs.gov', '2022-06-04');
insert into employee (id, name, email, birthday) values (16, 'Darrell', 'dlibbief@mtv.com', '2022-05-19');
insert into employee (id, name, email, birthday) values (17, 'Lolly', 'lconwsg@answers.com', '2022-09-12');
insert into employee (id, name, email, birthday) values (18, 'Margy', 'mkingsnodeh@go.com', '2022-10-08');
insert into employee (id, name, email, birthday) values (19, 'Artus', 'aanwelli@topsy.com', '2022-07-16');
insert into employee (id, name, email, birthday) values (20, 'Chrisy', 'ctidmanj@unc.edu', '2022-03-14');
insert into employee (id, name, email, birthday) values (21, 'Stoddard', 'srobeletk@over-blog.com', '2022-06-05');
insert into employee (id, name, email, birthday) values (22, 'Tiebold', 'tpaolozzil@mtv.com', '2022-11-05');
insert into employee (id, name, email, birthday) values (23, 'Temple', 'tgodartm@ftc.gov', '2022-12-15');
insert into employee (id, name, email, birthday) values (24, 'Vincent', 'vcolleten@issuu.com', '2022-08-12');
insert into employee (id, name, email, birthday) values (25, 'Tremayne', 'telhamo@nasa.gov', '2022-05-23');
insert into employee (id, name, email, birthday) values (26, 'Pincas', 'psansp@senate.gov', '2023-01-02');
insert into employee (id, name, email, birthday) values (27, 'Stanislaw', 'sbrislaneq@fc2.com', '2022-10-31');
insert into employee (id, name, email, birthday) values (28, 'Violet', 'vgoscombr@seesaa.net', '2022-06-25');
insert into employee (id, name, email, birthday) values (29, 'Buddie', 'bblackallers@people.com.cn', '2022-12-31');
insert into employee (id, name, email, birthday) values (30, 'Daffie', 'dspittlet@theguardian.com', '2022-06-17');
insert into employee (id, name, email, birthday) values (31, 'Engracia', 'eelementu@boston.com', '2023-02-13');
insert into employee (id, name, email, birthday) values (32, 'Felice', 'fmoneypennyv@umich.edu', '2022-09-27');
insert into employee (id, name, email, birthday) values (33, 'Rand', 'rtemplew@xinhuanet.com', '2022-07-27');
insert into employee (id, name, email, birthday) values (34, 'Marje', 'mgilex@trellian.com', '2022-10-04');
insert into employee (id, name, email, birthday) values (35, 'Alysa', 'afishbourny@desdev.cn', '2023-02-05');
insert into employee (id, name, email, birthday) values (36, 'Lynnette', 'lsextonez@plala.or.jp', '2022-07-11');
insert into employee (id, name, email, birthday) values (37, 'Zeb', 'zkemmet10@aboutads.info', '2022-04-09');
insert into employee (id, name, email, birthday) values (38, 'Sawyer', 'srudwell11@ucoz.com', '2022-11-19');
insert into employee (id, name, email, birthday) values (39, 'Georgine', 'gvicioso12@t.co', '2022-09-21');
insert into employee (id, name, email, birthday) values (40, 'Suzette', 'scaulier13@cargocollective.com', '2022-04-19');
insert into employee (id, name, email, birthday) values (41, 'Merrily', 'mrigard14@blinklist.com', '2022-11-04');
insert into employee (id, name, email, birthday) values (42, 'Merill', 'mostick15@deviantart.com', '2022-08-27');
insert into employee (id, name, email, birthday) values (43, 'Solly', 'sbillitteri16@statcounter.com', '2022-11-13');
insert into employee (id, name, email, birthday) values (44, 'Maye', 'moflannery17@i2i.jp', '2022-03-19');
insert into employee (id, name, email, birthday) values (45, 'Les', 'lbissett18@hhs.gov', '2023-01-14');
insert into employee (id, name, email, birthday) values (46, 'Perry', 'ptooze19@acquirethisname.com', '2022-05-09');
insert into employee (id, name, email, birthday) values (47, 'Steffane', 'saharoni1a@mysql.com', '2022-09-11');
insert into employee (id, name, email, birthday) values (48, 'Dalia', 'dfishleigh1b@huffingtonpost.com', '2022-06-23');
insert into employee (id, name, email, birthday) values (49, 'Budd', 'brapin1c@cpanel.net', '2022-03-10');
insert into employee (id, name, email, birthday) values (50, 'Timmie', 'tgerge1d@adobe.com', '2022-10-08');
```

- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```SQL
update employee set email = 'mail@mail.com' where id = 50;

update employee set name = 'Peri' where id = 46;

update employee set birthday = '2023-02-02' where id = 50;

update employee set email = 'mail@mail.com' where id > 46;

update employee set email = 'mail1@mail.com' where id = 50;

```

- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```SQL
delete from employee where id = 50;

delete from employee where name = 'Peri';

delete from employee where id > 48;

delete from employee where email = 'mail1@mail.com';

delete from employee where birthday = '2023-02-02';

```
