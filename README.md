# Project-SQL-relationship-python
This project about learning SQL relationship in python (In Indonesia)

Kita dapat membuat relasi antar kolom untuk satu tabel ke tabel lain. Untuk melakukan hal tersebut maka sekarang kita akan belajar tentang relationship. Dimana relationship:
- Mengizinkan kita untuk menghindari duplikat data
Misalnya: kita memiliki tabel universitas yang mempunyai relasi dengan tabel mahasiswa. Kita dapat mengetahui jurusan yang diambil dari mahasiswa tersebut dari tabel mahasiswa. Sehingga ketika kita ingin menginput data baru ke tabel universitas, maka kita tinggal menyalin kolom jurusan dari tabel mahasiswa tersebut tanpa takut terjadi duplikat data.
- Mempermudah untuk melakukan perubahan data
Sama halnya dengan contoh sebelumnya, selain untuk menginput data baru kita juga akan lebih dipermudah untuk meng-update data jika kedua tabel tersebut memiliki relasi.
- Berguna untuk membagi informasi dari tabel
Setiap tabel memiliki tipe data serta primary key dan foreign key di setiap kolom, kita dapat mengetahui relasi antar kolom dari masing - masing tabel tersebut.
Automatic Joins:
Sekarang untuk menampilkan data untuk populasi di tahun 2008 dari tabel Census serta abbreviation (singkatan) dari tabel State_Fact:
Langkah pertama dan perlu dicatat, kita perlu membuat engine, string koneksi ke database serta akses ke tabel dari database census.sqlite.
Kemudian kita tuliskan perintah SQL di dalam variabel stmt untuk menampilkan data dari kolom pop2008 dari tabel Census  dan abbreviation dari tabel State_Fact. Lalu kita tampilkan dengan perintah execute(stmt).
Join:
- Menerima tabel dan ekspresi opsional yang menjelaskan bagaimana kedua tabel tersebut saling berhubungan
- Ekspresi tidak diperlukan jika hubungannya telah ditentukan sebelumnya dan tersedia melalui refleksi
- Setelah klausa select () dan sebelumnya ke klausa where (), order_by atau group_by ()

Select_from:
- Digunakan untuk mengganti klausa FROM default yang diturunkan dengan gabungan
- Menggabungkan klausa join()
