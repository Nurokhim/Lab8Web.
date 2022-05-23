TUGAS PRATIKUM 8 PERTEMUAN 10

PEMROGRAMAN WEB

TEKNIK INFORMATIKA

UNIVERSITAS PELITA BANGSA

NAMA : Nurokhim

NIM : 312010064

KELAS : TI.20.D1

DOSEN : Agung Nugroho,S.Kom.,M.Kom Instruksi Praktikum

<b>Langkah_Langkah Pratikum</b>

Persiapan

Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.

<b>Menjalankan MySQL Server</b>

Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![image](https://user-images.githubusercontent.com/101801920/169657712-99748993-e512-435c-b54c-da59c35e6d0b.png)

<b>Mengakses MySQL Client menggunakan PHP MyAdmin</b>

Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser: http://localhost/phpmyadmin/

<b>Membuat Database</b>

![image](https://user-images.githubusercontent.com/101801920/169658133-95e330a3-a881-4091-944b-97324b69bd28.png)

<b>Membuat Tabel</b>

![image](https://user-images.githubusercontent.com/101801920/169658313-9bd8b183-16fe-47f8-bb0a-0e10ec03d57f.png)

<b>Menambahkan Data</b>

![image](https://user-images.githubusercontent.com/101801920/169658492-be59622a-0942-4fbc-85ad-f13813a6a702.png)

![image](https://user-images.githubusercontent.com/101801920/169659513-bdf141bf-3720-4b42-810f-d6a2774c4632.png)

<b>Membuat Program CRUD</b>

Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![image](https://user-images.githubusercontent.com/101801920/169659581-4dedb4bf-c771-4dc8-afb9-3856c3a77f87.png)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/lab8_php_database/

![image](https://user-images.githubusercontent.com/101801920/169659649-f0b36899-e086-4866-8db5-3bb4745329a1.png)

<b>Membuat file koneksi database</b>

Buat file baru dengan nama koneksi.php

![image](https://user-images.githubusercontent.com/101801920/169660337-9ed871bd-1d32-443e-bd11-f16a360e7eda.png)

Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”;

![image](https://user-images.githubusercontent.com/101801920/169660206-f3cfb197-b93e-429a-8286-2e7ec48b7f33.png)

<b>Membuat file index untuk menampilkan data (Read)</b>

Buat file baru dengan nama index.php

![image](https://user-images.githubusercontent.com/101801920/169660866-46837551-5b66-499f-8ed5-a3e5ce18815b.png)

![image](https://user-images.githubusercontent.com/101801920/169660902-ca597aa6-dcca-4312-b30a-fa3c93dc17b0.png)

![image](https://user-images.githubusercontent.com/101801920/169660917-f756b29f-bb02-492f-aac4-7c1aedc9a421.png)

<b>Menambah Data (Create)</b>

Buat file baru dengan nama tambah.php

![image](https://user-images.githubusercontent.com/101801920/169795085-d9d20f90-7f27-4f95-b09c-690f57127c9b.png)

![image](https://user-images.githubusercontent.com/101801920/169795240-893ae6f3-f9c4-47ce-87d7-708e5bfc7abd.png)

![image](https://user-images.githubusercontent.com/101801920/169795444-00ff92ae-6752-42a4-8bdc-b826a6cf5baa.png)

![image](https://user-images.githubusercontent.com/101801920/169800544-d997e591-c9e8-4a68-9c61-bf5c832e442d.png)

<b>Mengubah Data (Update)</b>

Buat file baru dengan nama ubah.php

![image](https://user-images.githubusercontent.com/101801920/169800696-c102e2d8-c7c2-43b6-8ae8-274cb9f9a79e.png)

![image](https://user-images.githubusercontent.com/101801920/169800782-e30ad48a-b263-44a2-aea6-82d19ae1e13f.png)

![image](https://user-images.githubusercontent.com/101801920/169800930-688c0c5c-225a-49fb-a7a8-3af001cb2df9.png)

![image](https://user-images.githubusercontent.com/101801920/169801042-042c461a-c4fd-471b-997a-2566b3db6eb3.png)

![image](https://user-images.githubusercontent.com/101801920/169801144-fadb82b5-19c6-42b8-aece-e4c6238977a9.png)

<b>Menghapus Data (Delete)</b>

Buat file baru dengan nama hapus.php

![image](https://user-images.githubusercontent.com/101801920/169801753-7ef115f2-5da0-424b-9057-a03510c427f7.png)

<b>Data sebelum di hapus</b>

![image](https://user-images.githubusercontent.com/101801920/169802346-4864253b-e397-40a7-b060-f6763e2b41e6.png)

<b>Data sesudah di hapus</b>

![image](https://user-images.githubusercontent.com/101801920/169802594-9462e9b5-4e5f-443a-a414-800514f64a41.png)
