
# Patika.dev - SQL 

1.	test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```sql
CREATE TABLE employee (
id int,
name varchar(50),
birthday date,
email varchar(100) 
);
```

2.	Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```sql
insert into employee (id, name, birthday, email) values (1, 'Katie Elphick', '1/19/2023', 'kelphick0@pen.io');
insert into employee (id, name, birthday, email) values (2, 'Bonnee Darrington', '2/11/2023', 'bdarrington1@stumbleupon.com');
insert into employee (id, name, birthday, email) values (3, 'Viki Cherry', '10/5/2023', 'vcherry2@nasa.gov');
insert into employee (id, name, birthday, email) values (4, 'Cristobal Scoggin', '1/6/2023', 'cscoggin3@multiply.com');
insert into employee (id, name, birthday, email) values (5, 'Mechelle Hasney', '11/21/2022', 'mhasney4@altervista.org');
insert into employee (id, name, birthday, email) values (6, 'Redford Gregg', '11/27/2022', 'rgregg5@tripod.com');
insert into employee (id, name, birthday, email) values (7, 'Felisha Ludron', '7/4/2023', 'fludron6@live.com');
insert into employee (id, name, birthday, email) values (8, 'Petronilla Cacacie', '6/14/2023', 'pcacacie7@instagram.com');
insert into employee (id, name, birthday, email) values (9, 'Nilson Blancowe', '10/23/2023', 'nblancowe8@uol.com.br');
insert into employee (id, name, birthday, email) values (10, 'Sharona Laroux', '10/23/2023', 'slaroux9@miitbeian.gov.cn');
insert into employee (id, name, birthday, email) values (11, 'Rudolph Midson', '12/19/2022', 'rmidsona@patch.com');
insert into employee (id, name, birthday, email) values (12, 'Mariel Ellingford', '5/17/2023', 'mellingfordb@scribd.com');
insert into employee (id, name, birthday, email) values (13, 'Thorny Dinse', '11/23/2022', 'tdinsec@unicef.org');
insert into employee (id, name, birthday, email) values (14, 'Reinwald Millis', '3/2/2023', 'rmillisd@seattletimes.com');
insert into employee (id, name, birthday, email) values (15, 'Evangelia Ritchley', '10/16/2023', 'eritchleye@wikispaces.com');
insert into employee (id, name, birthday, email) values (16, 'Dale Karchewski', '4/17/2023', 'dkarchewskif@google.co.jp');
insert into employee (id, name, birthday, email) values (17, 'Gerard Dimitrijevic', '9/27/2023', 'gdimitrijevicg@slate.com');
insert into employee (id, name, birthday, email) values (18, 'Nikki Rubinovitch', '7/23/2023', 'nrubinovitchh@squarespace.com');
insert into employee (id, name, birthday, email) values (19, 'Brandtr Doddemeede', '6/17/2023', 'bdoddemeedei@mapquest.com');
insert into employee (id, name, birthday, email) values (20, 'Aymer Laurenzi', '11/18/2022', 'alaurenzij@seattletimes.com');
insert into employee (id, name, birthday, email) values (21, 'Atlante Leak', '11/20/2022', 'aleakk@ameblo.jp');
insert into employee (id, name, birthday, email) values (22, 'Bridgette Boow', '8/17/2023', 'bboowl@bloglines.com');
insert into employee (id, name, birthday, email) values (23, 'Diena Leathard', '10/14/2023', 'dleathardm@ox.ac.uk');
insert into employee (id, name, birthday, email) values (24, 'Phillipe Gozzard', '1/5/2023', 'pgozzardn@hostgator.com');
insert into employee (id, name, birthday, email) values (25, 'Min Leece', '12/8/2022', 'mleeceo@uol.com.br');
insert into employee (id, name, birthday, email) values (26, 'Kyla Giddens', '9/2/2023', 'kgiddensp@squarespace.com');
insert into employee (id, name, birthday, email) values (27, 'Moishe Swanton', '4/1/2023', 'mswantonq@accuweather.com');
insert into employee (id, name, birthday, email) values (28, 'Ferdinande Hiscoke', '8/16/2023', 'fhiscoker@gnu.org');
insert into employee (id, name, birthday, email) values (29, 'Bernard Pummery', '2/5/2023', 'bpummerys@google.fr');
insert into employee (id, name, birthday, email) values (30, 'Yvon Geake', '10/16/2023', 'ygeaket@angelfire.com');
insert into employee (id, name, birthday, email) values (31, 'Liam Paulson', '4/25/2023', 'lpaulsonu@army.mil');
insert into employee (id, name, birthday, email) values (32, 'Mikael Eakley', '1/8/2023', 'meakleyv@si.edu');
insert into employee (id, name, birthday, email) values (33, 'Corbett Slides', '10/20/2023', 'cslidesw@techcrunch.com');
insert into employee (id, name, birthday, email) values (34, 'Giulia Olivelli', '2/2/2023', 'golivellix@free.fr');
insert into employee (id, name, birthday, email) values (35, 'Yuri Goodwill', '4/10/2023', 'ygoodwilly@sbwire.com');
insert into employee (id, name, birthday, email) values (36, 'Joane Ivanitsa', '8/23/2023', 'jivanitsaz@symantec.com');
insert into employee (id, name, birthday, email) values (37, 'Fifi Benaine', '4/5/2023', 'fbenaine10@dailymail.co.uk');
insert into employee (id, name, birthday, email) values (38, 'Even Sapp', '11/2/2022', 'esapp11@utexas.edu');
insert into employee (id, name, birthday, email) values (39, 'Lorrin Claw', '6/29/2023', 'lclaw12@4shared.com');
insert into employee (id, name, birthday, email) values (40, 'Alysia Easton', '11/28/2022', 'aeaston13@stumbleupon.com');
insert into employee (id, name, birthday, email) values (41, 'Etti Basnett', '12/17/2022', 'ebasnett14@elegantthemes.com');
insert into employee (id, name, birthday, email) values (42, 'Petronilla Rudram', '7/20/2023', 'prudram15@360.cn');
insert into employee (id, name, birthday, email) values (43, 'Rosalyn Beamson', '4/18/2023', 'rbeamson16@icq.com');
insert into employee (id, name, birthday, email) values (44, 'Ara Gilliat', '6/8/2023', 'agilliat17@wired.com');
insert into employee (id, name, birthday, email) values (45, 'Reinold Foxcroft', '4/5/2023', 'rfoxcroft18@wikia.com');
insert into employee (id, name, birthday, email) values (46, 'Swen Mantha', '1/26/2023', 'smantha19@hao123.com');
insert into employee (id, name, birthday, email) values (47, 'Laural Marlowe', '11/26/2022', 'lmarlowe1a@smh.com.au');
insert into employee (id, name, birthday, email) values (48, 'Jasmine Quibell', '12/6/2022', 'jquibell1b@state.gov');
insert into employee (id, name, birthday, email) values (49, 'Dick Rasch', '8/10/2023', 'drasch1c@time.com');
insert into employee (id, name, birthday, email) values (50, 'Nathanil Zamorano', '4/12/2023', 'nzamorano1d@smugmug.com');
```

3.	Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
UPDATE employee
SET name = 'Dora Caldow',
birthday = '4/2/2023',
email = 'dcaldow2r@epa.gov'
WHERE id = 1;


UPDATE employee
SET name = 'Antonin Gorey',
birthday = '4/28/2023',
email = 'agorey2g@blogger.com'
WHERE id = 2;

UPDATE employee
SET name = 'Tony Phettis',
birthday = '2/22/2023',
email = 'tphettis21@vimeo.com'
WHERE id = 50;

UPDATE employee
SET name = 'Shaun Goodger',
birthday = '10/25/2023',
email = 'sgoodger1u@gizmodo.com'
WHERE id = 48;

UPDATE employee
SET name = 'Darsey Rennick',
birthday = '11/21/2022',
email = 'drennick1n@163.com'
WHERE id = 49;
```

4.	Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee
WHERE id = 1;

DELETE FROM employee
WHERE id = 2;

DELETE FROM employee
WHERE id = 50;

DELETE FROM employee
WHERE id = 48;

DELETE FROM employee
WHERE id = 49;
```



[Patika.dev - SQL kursuna gitmek için tıklayın.](https://academy.patika.dev/tr/courses/sql)
