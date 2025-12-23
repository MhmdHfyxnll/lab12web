# Nama : Muhammad Hafiyainul Yakin Wahid
# NIM : 312410164


```
Implementasi Login dan Pagination Menggunakan PHP dan MySQL

1. Deskripsi

Aplikasi web ini dibuat untuk memenuhi tugas Praktikum 13, dengan tujuan mengimplementasikan fitur autentikasi (login) menggunakan session serta pagination pada tampilan data menggunakan PHP dan MySQL. Pagination digunakan untuk membatasi jumlah data yang ditampilkan pada setiap halaman sehingga tampilan lebih terstruktur dan efisien.

2. Fitur Aplikasi

Sistem Login dan Logout

Autentikasi menggunakan Session

Pembatasan akses halaman (Protected Page)

Pagination data menggunakan LIMIT dan OFFSET

Antarmuka sederhana dan interaktif

3. Struktur Folder
praktikum13/
├── index.php        // Halaman utama (pagination data)
├── login.php        // Form login
├── logout.php       // Proses logout
├── auth.php         // Proteksi halaman
├── koneksi.php      // Koneksi database
└── style.css        // Styling antarmuka

4. Teknologi yang Digunakan

PHP

MySQL

HTML

CSS

Apache (XAMPP)

5. Cara Menjalankan Aplikasi

Aktifkan Apache dan MySQL melalui XAMPP

Buat dan import database praktikum13 melalui phpMyAdmin

Simpan folder proyek ke dalam direktori htdocs

Akses aplikasi melalui browser:

http://localhost/praktikum13/login.php

6. Informasi Akun Login
Username : admin  
Password : admin123

7. Penjelasan Singkat Pagination

Pagination diimplementasikan menggunakan query SQL LIMIT dan OFFSET untuk membatasi jumlah data yang ditampilkan pada setiap halaman. Jumlah halaman ditentukan berdasarkan total data yang tersedia di database.

8. Kesimpulan

Dengan dibuatnya aplikasi ini, mahasiswa dapat memahami konsep session pada PHP, pembatasan akses halaman, serta pagination data menggunakan MySQL sebagai bagian dari pengembangan aplikasi web dinamis.
```
