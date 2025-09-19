Praktikum PBO Pertemuan 5
==========================

Deskripsi
------------
Project ini adalah hasil praktikum Pemrograman Berorientasi Objek (PBO) pertemuan kelima.
Fokus utamanya adalah implementasi CRUD (Create, Read, Update, Delete) dengan menggunakan:
- Java sebagai bahasa pemrograman utama
- Java Swing untuk membuat tampilan GUI
- PostgreSQL sebagai database
- JDBC (Java Database Connectivity) untuk koneksi database

Aplikasi ini memungkinkan pengguna untuk:
- Menambahkan data barang baru (Create)
- Melihat data barang (Read)
- Mengubah data barang (Update)
- Menghapus data barang (Delete)
- Clear untuk menghapus semua entri
- Reset untuk mengosongkan form input

Selain itu, project ini juga menambahkan contoh Custom Exception untuk mengecek tinggi badan pengguna.

Struktur Project
-------------------
1. Koneksi Database (PostgreSQL + JDBC)
   - Connection, DriverManager, PreparedStatement, ResultSet, Statement, SQLException

2. Antarmuka GUI (Java Swing)
   - JOptionPane untuk pop-up message
   - DefaultTableModel untuk tabel data

3. Operasi CRUD
   - Insert : Menambahkan data
   - Update : Mengubah data
   - Delete : Menghapus data tertentu
   - Clear  : Menghapus semua entri
   - Reset  : Mengosongkan input

4. Custom Exception
   - TinggibadanTidakMemenuhi → Exception khusus jika tinggi badan < 165 cm
   - Wahana → Class utama yang menggunakan exception

⚙Cara Menjalankan
-------------------
1. Buat database PostgreSQL baru dengan nama:
   DB_PBO_PRAK5

2. Import source code Java ke IDE (disarankan NetBeans karena mendukung GUI Builder)

3. Pastikan library JDBC PostgreSQL sudah ditambahkan

4. Jalankan program untuk mencoba fitur CRUD dan Custom Exception
 
Author
---------
Ananda Farid Firdaus
Universitas Islam Negeri Sunan Ampel Surabaya
Program Studi Sistem Informasi – 2025
