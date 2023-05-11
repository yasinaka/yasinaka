### 1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
CREATE TABLE employee (  
  id INTEGER,  
  first_name VARCHAR(50),  
  last_name Varchar(50),  
  birthday DATE,  
  email VARCHAR(100)        );  
### 2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
insert into employee (id, first_name, last_name, birthday, email) values (1, 'Levi', 'Dragge', '1939-09-12', 'ldragge0@discuz.net');   
...  
...  
...  
### 3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
A) UPDATE employee SET first_name = 'Yasin' WHERE id = 1;  
B) UPDATE employee SET last_name = 'Aka' WHERE id = 1;  
C) UPDATE employee SET birthday = '1998-04-01' WHERE id = 1;  
D)UPDATE employee SET email = 'yasinaka98@gmail.com' WHERE id = 1;  
### 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.  
A) DELETE FROM employee   WHERE id = 2;  
B) DELETE FROM employee WHERE first_name = 'Michelle';  
C) DELETE FROM employee WHERE last_name = 'Barwack';  
D) DELETE FROM employee WHERE birthday = '2012-02-20';   
E) DELETE FROM employee WHERE email = 'yasinaka98@gmail.com';   

