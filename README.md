# lab7web
## Nama : Nur Salsabila
## NIM  : 312310344
## kelas :TI 23 A.4

Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama LABWEB7 pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya. Langkah-langkah Praktikum Persiapan Untuk memulai membuat kode php, perlu disiapkan web server dan interpreter PHP terlebih dahulu. Web servar yang kita gunakan adalah Apache 2 dan interpreter PHP 7. Untuk memudahkan proses praktikum, kita gunakan aplikasi bundle web server yaitu XAMPP.

Install XAMPP
Unduh XAMPP dari https://www.apachefriends.org/download.html dan pilih versi portable untuk memudahkan proses installasi. Kemudian extract file tersebut, seusikan direktorinya.

Menjalankan Web Server

Untuk menjalankan web server dari menu XAMPP Control.
Gambar1. XAMPP Control
![Screenshot 2024-11-15 191605](https://github.com/user-attachments/assets/c79ef863-42f5-4081-9723-3daff78d6ea2)


• Uji coba apakah server sudah berkerja dengan baik http://127.0.0.1 atau http://localhost Tampil halaman utama XAMPP jika server sudah berkerja dengan baik. • Dokumen Website Semua file website tempatkan di direktori: \xampp\htdocs
• Database MySQL Direktori: \xampp\mysql
Manajemen database: http://localhost/phpmyadmin

Memulai PHP

Buat folder LABWEB7 pada root directory web server (D:\xampp\htdocs)
Gambar2. Directory Lab7
![Screenshot 2024-11-15 191645](https://github.com/user-attachments/assets/056061a6-5875-4234-aa00-22b8eb2f39d7)


Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/LABWEB7/
Gambar3. Tampilan Web Server

![Screenshot 2024-11-15 191811](https://github.com/user-attachments/assets/cadde31e-080a-4584-82d7-10d702d86efd)


PHP Dasar

Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat kode seperti berikut.
![Screenshot 2024-11-13 170953](https://github.com/user-attachments/assets/8bca6586-e014-406f-91c5-83981d4c1d5a)

Hasilnya
![Screenshot 2024-11-13 170816](https://github.com/user-attachments/assets/9a1d6bd0-6dcb-4ff8-b1fd-023ced89628a)

Variable PHP

Menambahkan variable pada program.
![Screenshot 2024-11-13 171427](https://github.com/user-attachments/assets/96888b01-bb3e-422d-9d46-eb30f273702e)

Hasilnya
![Screenshot 2024-11-13 171308](https://github.com/user-attachments/assets/3f80e1a8-0889-4b99-8737-68a46d88d815)

Predefine Variable $_GET

![Screenshot 2024-11-13 173438](https://github.com/user-attachments/assets/6f98dd1e-fa51-49a1-b28a-74fb91c5f3ae)

Hasilnya
![Screenshot 2024-11-13 173409](https://github.com/user-attachments/assets/c5b42d7f-8ed0-4d33-9cad-a391c9c8ded1)

Membuat Form Input

![Screenshot 2024-11-13 182118](https://github.com/user-attachments/assets/06f09dc7-9bf5-4b2b-91a2-9d8b3d8f6fb5)

Hasilnya 
![Screenshot 2024-11-13 182048](https://github.com/user-attachments/assets/14f9ac7d-5f40-48af-ac9d-52d6e47f39a9)

Operator

![Screenshot 2024-11-14 112711](https://github.com/user-attachments/assets/2314eaae-c84a-409d-9203-4599fc831425)

Hasilnya 
![Screenshot 2024-11-14 112614](https://github.com/user-attachments/assets/2e8249ec-3835-4fef-8c86-6b3be6979467)

Kondisi IF

![Screenshot 2024-11-14 112854](https://github.com/user-attachments/assets/35112a5b-8d64-48ec-920f-22c0705f48f3)

Hasilnya
![Screenshot 2024-11-14 112828](https://github.com/user-attachments/assets/96704599-1dba-4e83-8de6-3ed395de7197)

Kondisi Switch

![Screenshot 2024-11-14 113123](https://github.com/user-attachments/assets/81fabe96-4df8-4a16-8c1e-96d4e6d538df)

Hasilnya
![Screenshot 2024-11-14 163818](https://github.com/user-attachments/assets/5b972f17-0d3c-466c-8b58-e51ae8fd0364)

Perulangan for

![Screenshot 2024-11-14 113310](https://github.com/user-attachments/assets/08d61a30-af82-4c0e-b08b-5dfa4dc885e3)

Hasilnya
![Screenshot 2024-11-14 113654](https://github.com/user-attachments/assets/260a9d2c-ad41-432e-b9cd-aa2d19af040b)

Perulangan while

![Screenshot 2024-11-14 113855](https://github.com/user-attachments/assets/81865f3a-163c-4b1e-8129-c4c060141af8)

Hasilnya
![Screenshot 2024-11-14 113837](https://github.com/user-attachments/assets/f56989a3-a089-46ed-b86a-2ef03536bd5f)

Perulangan dowhile

![Screenshot 2024-11-14 114008](https://github.com/user-attachments/assets/ee541209-e9d4-4857-aedb-d59cc5963244)

Hasilnya
![Screenshot 2024-11-14 113950](https://github.com/user-attachments/assets/01a00f67-8011-4360-a785-080cde905122)


Pertanyaan dan Tugas

Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang berbeda-beda sesuai pilihan pekerjaan.

JAWAB

![Screenshot 2024-11-14 114349](https://github.com/user-attachments/assets/0f6582a2-76ee-4c11-8259-4695565769d4)

![Screenshot 2024-11-14 114414](https://github.com/user-attachments/assets/5226d0df-065e-4368-ba8e-cdb108836b8f)

Hasilnya
![Screenshot 2024-11-14 114315](https://github.com/user-attachments/assets/dbb38005-4e95-43ae-b7a6-fa4c7284bb8f)