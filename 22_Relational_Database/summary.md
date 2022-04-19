#Relasi Database
Pada basis data relasional dikenal dengan istilah relasi. Relasi yang dimaksud adalah berupa tabel yang terdiri atas baris dan kolom. Kumpulan relasi/tabel yang terkait akan membentuk basis data relasional. 

#
Beberapa hal yang harus kamu ketahui tentang foreign key & primary key:
Harus unik
Tabel hanya boleh memiliki satu primary key, namun dalam beberapa kasus boleh lebih dari 1 primary key (composite key)
Tabel boleh memiliki lebih dari satu foreign key
Foreign key digunakan untuk membuat relasi antar tabel

#
Ada beberapa jenis relasi database, yang akan dibahas adalah:
-One to One
Relasi One to One adalah relasi yang mana setiap satu baris data pada tabel pertama hanya berhubungan dengan satu baris pada tabel kedua.
-One to Many
Relasi One to Many adalah relasi yang mana setiap satu baris data pada tabel pertama berhubungan dengan lebih dari satu baris pada tabel kedua.
-Many to Many
Relasi Many to Many adalah relasi yang mana setiap lebih dari satu baris data dari tabel pertama berhubungan dengan lebih dari satu baris data pada tabel kedua. Artinya, kedua tabel masing-masing dapat mengakses banyak data dari tabel yang direlasikan. Dalam hal ini, relasi Many to Many akan menghasilkan tabel ketiga sebagai perantara tabel kesatu dan tabel kedua sebagai tempat untuk menyimpan foreign key dari masing-masing tabel. 

# RDBMS
Merupakan software yang menggunakan relational database model sebagai dasarnya, contoh : MySQL. Jenis perintah pada SQL yaitu DDL, DML, dan DCL
Tipe data pada MySQL yaitu Num,Huruf,Date

#Task
Lakukan relasi database one to one, yang mana akan menghubungkan id_anggota pada tabel keterangan dengan nama pada tabel anggota.
Lakukan relasi database one to many, yang mana akan menghubungkan id pada tabel anggota dengan pelajaran pada tabel keterangan. 
