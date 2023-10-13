- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

        CREATE TABLE employee(
            id INTEGER,
            name VARCHAR(50),
            birthday DATE,
            email VARCHAR(100)
        );

- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

        insert into employee (id, name, birthday, email) values (1, 'Daffy Truran', '2023-07-21', 'dtruran0@constantcontact.com');
        insert into employee (id, name, birthday, email) values (2, 'Francklin Daveridge', '2023-07-01', 'fdaveridge1@un.org');
        insert into employee (id, name, birthday, email) values (3, 'Ailene Vickress', '2023-03-19', 'avickress2@i2i.jp');
        insert into employee (id, name, birthday, email) values (4, 'Barbara-anne Bartunek', '2023-06-26', 'bbartunek3@ezinearticles.com');
        insert into employee (id, name, birthday, email) values (5, 'Salvatore Ravenscroft', '2023-06-25', 'sravenscroft4@csmonitor.com');
        insert into employee (id, name, birthday, email) values (6, 'Josefina Jecks', '2023-04-06', 'jjecks5@boston.com');
        insert into employee (id, name, birthday, email) values (7, 'Dwight Bomb', '2023-06-16', 'dbomb6@nih.gov');
        insert into employee (id, name, birthday, email) values (8, 'Jasmin Tipple', '2023-06-07', 'jtipple7@sfgate.com');
        insert into employee (id, name, birthday, email) values (9, 'Misty Matczak', '2023-04-30', 'mmatczak8@google.de');
        insert into employee (id, name, birthday, email) values (10, 'Frederigo Iscowitz', '2023-08-11', 'fiscowitz9@bing.com');
        insert into employee (id, name, birthday, email) values (11, 'Mitch Block', '2023-06-26', 'mblocka@drupal.org');
        insert into employee (id, name, birthday, email) values (12, 'Ernestus Boxall', '2023-08-15', 'eboxallb@geocities.com');
        insert into employee (id, name, birthday, email) values (13, 'Theodor Yewdall', '2023-07-11', 'tyewdallc@marriott.com');
        insert into employee (id, name, birthday, email) values (14, 'Dorthea Weekes', '2023-05-12', 'dweekesd@gov.uk');
        insert into employee (id, name, birthday, email) values (15, 'Quintus Birrel', '2023-06-25', 'qbirrele@mail.ru');
        insert into employee (id, name, birthday, email) values (16, 'Brooke Tidman', '2023-07-02', 'btidmanf@histats.com');
        insert into employee (id, name, birthday, email) values (17, 'Xena Jaze', '2022-11-22', 'xjazeg@domainmarket.com');
        insert into employee (id, name, birthday, email) values (18, 'Gradey Reville', '2023-04-15', 'grevilleh@marketwatch.com');
        insert into employee (id, name, birthday, email) values (19, 'Harrie Orrobin', '2023-05-24', 'horrobini@zimbio.com');
        insert into employee (id, name, birthday, email) values (20, 'Deana Jaskowicz', '2023-07-11', 'djaskowiczj@cyberchimps.com');
        insert into employee (id, name, birthday, email) values (21, 'Beck Martlew', '2023-07-18', 'bmartlewk@bloomberg.com');
        insert into employee (id, name, birthday, email) values (22, 'Doug Silcox', '2023-07-14', 'dsilcoxl@yellowbook.com');
        insert into employee (id, name, birthday, email) values (23, 'Gerick Dobbings', '2023-05-29', 'gdobbingsm@wp.com');
        insert into employee (id, name, birthday, email) values (24, 'Aldus Caswall', '2023-01-18', 'acaswalln@gravatar.com');
        insert into employee (id, name, birthday, email) values (25, 'Silva Cardero', '2023-07-09', 'scarderoo@foxnews.com');
        insert into employee (id, name, birthday, email) values (26, 'Ravid Kundert', '2023-01-01', 'rkundertp@ovh.net');
        insert into employee (id, name, birthday, email) values (27, 'Lyn Carleton', '2023-01-14', 'lcarletonq@answers.com');
        insert into employee (id, name, birthday, email) values (28, 'Leisha Colgan', '2023-06-18', 'lcolganr@nyu.edu');
        insert into employee (id, name, birthday, email) values (29, 'Iris Berthe', '2023-08-15', 'iberthes@imageshack.us');
        insert into employee (id, name, birthday, email) values (30, 'Sharleen Reiach', '2022-11-14', 'sreiacht@blogtalkradio.com');
        insert into employee (id, name, birthday, email) values (31, 'Rocky Crier', '2023-07-29', 'rcrieru@arizona.edu');
        insert into employee (id, name, birthday, email) values (32, 'Lazar Kalb', '2023-05-05', 'lkalbv@shop-pro.jp');
        insert into employee (id, name, birthday, email) values (33, 'Trevor Corsan', '2022-12-09', 'tcorsanw@discovery.com');
        insert into employee (id, name, birthday, email) values (34, 'Nanete Durdle', '2023-08-10', 'ndurdlex@statcounter.com');
        insert into employee (id, name, birthday, email) values (35, 'Roxie Bisiker', '2023-02-19', 'rbisikery@sciencedirect.com');
        insert into employee (id, name, birthday, email) values (36, 'Cornelius Lean', '2022-10-08', 'cleanz@taobao.com');
        insert into employee (id, name, birthday, email) values (37, 'Hans Feeley', '2022-11-06', 'hfeeley10@cnbc.com');
        insert into employee (id, name, birthday, email) values (38, 'Rebekkah Fane', '2023-03-08', 'rfane11@berkeley.edu');
        insert into employee (id, name, birthday, email) values (39, 'Silva Mattock', '2023-04-15', 'smattock12@github.com');
        insert into employee (id, name, birthday, email) values (40, 'Tobit Jorden', '2023-05-19', 'tjorden13@upenn.edu');
        insert into employee (id, name, birthday, email) values (41, 'Parnell Bunston', '2023-01-23', 'pbunston14@globo.com');
        insert into employee (id, name, birthday, email) values (42, 'Idalia Edmott', '2023-01-02', 'iedmott15@merriam-webster.com');
        insert into employee (id, name, birthday, email) values (43, 'Eryn Marsy', '2023-08-24', 'emarsy16@cnbc.com');
        insert into employee (id, name, birthday, email) values (44, 'Herta Gregolin', '2023-05-30', 'hgregolin17@bloglovin.com');
        insert into employee (id, name, birthday, email) values (45, 'Dorette Handrahan', '2023-06-20', 'dhandrahan18@51.la');
        insert into employee (id, name, birthday, email) values (46, 'Kingston Breagan', '2023-03-25', 'kbreagan19@wp.com');
        insert into employee (id, name, birthday, email) values (47, 'Tyrone MacDirmid', '2023-05-12', 'tmacdirmid1a@skyrock.com');
        insert into employee (id, name, birthday, email) values (48, 'Thayne Conkay', '2023-05-16', 'tconkay1b@flickr.com');
        insert into employee (id, name, birthday, email) values (49, 'Britta Caldecot', '2023-08-18', 'bcaldecot1c@facebook.com');
        insert into employee (id, name, birthday, email) values (50, 'Artemas Budleigh', '2023-01-26', 'abudleigh1d@msn.com');

- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

        UPDATE employee
        SET
            name = 'Oguzhan Pala'   	------------------- id si '1' olan kişinin name alanının güncellenmesi.
        WHERE id=1;
-------------------
        UPDATE employee
        SET
            birthday ='1997-01-01',		
            email='example@com.tr'		------------------- ismi A ile başlayıp s ile biten kişilerin birthday ve email alanının güncellenmesi.
        WHERE name LIKE 'A%s'
        RETURNING *;
-------------------
        UPDATE employee
        SET 
            name ='youngEmployee'		------------------- doğum tarihi 2023-06-01 tarihinden büyük kişilerin name alanının güncellenmesi.
        WHERE birthday > '2023-06-01'
        RETURNING *;
-------------------
        UPDATE employee
        SET
            name ='Example',
            birthday='2023-01-01'		------------------- id si 10'dan 15'e kadar olan kişilerin name ve birthday alanının güncellenmesi.
        WHERE id BETWEEN 10 AND 15;
--------------------
        UPDATE employee
        SET 
            email='example@com.tr'		------------------- email adresi '.com' ile biten kişilerin email alanının güncellenmesi.
        WHERE email LIKE '%.com'
        RETURNING *;

- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

        DELETE FROM employee
        WHERE id =2;					------------------- id si '2' olan kişinin silinmesi.
--------------------
        DELETE FROM employee
        WHERE name ILIKE '%a%a%a%'		-------------------- name alanının içinde 3 adet büyük küçük duyarsız 'a' olan kişilerin silinmesi. 
        RETURNING *;
--------------------
        DELETE FROM employee
        WHERE name ='Example'			-------------------- name alanı Example olan kişilerin silinmesi.
        RETURNING *;
--------------------
        DELETE FROM employee
        WHERE id>40;					-------------------- id si 40'dan büyük olan kişilerin silinmesi.
--------------------
        DELETE FROM employee
        WHERE 
            (id>10 AND id<20) OR		-------------------- id si 10-20 aralığındaki veya email adresi '.net' ile bitenlerin silinmesi.
            (email LIKE '%.net')
        RETURNING *;