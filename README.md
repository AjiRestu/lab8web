### Langkah -Langkah Pratikum

Alat -Alat yang dibutuhkan
- XAMPP
- Teks editor seperti Sublime text

Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah
database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan
melalui XAMPP.

## Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![](foto/1.PNG)

## Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka
melalui browser: http://localhost/phpmyadmin/

## Membuat Database

![](foto/2.PNG)

## Membuat Tabel

![](foto/3.PNG)

## Menambahkan Data

![](foto/4.PNG)

## Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![](foto/5.PNG)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab8_php_database/

![](foto/6.PNG)

## Membuat File Koneksi Database
Buatlah file baru di sublime text dengan nama koneksi.php

![](foto/7.PNG)

Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan
koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”;

![](foto/8.PNG)

## Membuat file index untuk menampilkan data (Read)
Buat file baru di sublime text dengan nama index.php

![](foto/9.PNG)
![](foto/10.PNG)

Untuk menampilkan file tersebut buka di browser:http://localhost/lab8_php_database/index.php

![](foto/11.PNG)

## Menambah Data (Create)
Buat file baru dengan nama tambah.php

![](foto/12.PNG)
![](foto/13.PNG)
![](foto/14.PNG)

Untuk menampilkan file tersebut buka di browser:http://localhost/lab8_php_database/tambah.php

![](foto/15.PNG)

## Mengubah Data (Update)
Buat file baru dengan nama ubah.php

![](foto/16.PNG)
![](foto/17.PNG)
![](foto/18.PNG)
![](foto/19.PNG)

Untuk menampilkan file tersebut buka di browser:http://localhost/lab8_php_database/ubah.php

![](foto/20.PNG)

![](foto/21.PNG)
Lihatlah pada tabel hp Realme 5 di bagian stok berhasil diganti

## Menghapus Data (Delete)
Buat file baru dengan nama hapus.php

![](foto/22.PNG)

before
![](foto/21.PNG

after
![](foto/23.PNG)
Lihatlah pada tabel hp Realme 7 sudah berhasil di hapus
