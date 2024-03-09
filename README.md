# Bookshelf Apps

### Deskripsi Proyek:
--------------------
Ini adalah proyek submission web untuk pemula di Dicoding yang bertujuan untuk membangun sebuah aplikasi web bernama Bookshelf Apps. Aplikasi ini memungkinkan pengguna untuk:
* Menambahkan Data Buku
* Menyimpan Data Buku
* Memindahkan Data Buku antar Rak
* Menghapus Data Buku dari Rak

### Kriteria Proyek:
-------------------

**1. Menambahkan Data Buku:**
- Bookshelf Apps dapat menambahkan data buku baru.
- Data buku disimpan sebagai objek JavaScript dengan struktur:
```
JavaScript
{
  id: string | number,
  title: string,
  author: string,
  year: number,
  isComplete: boolean,
}
```

* Contoh data buku:
```
JavaScript
{
  id: 3657848524,
  title: 'Harry Potter and the Philosopher\'s Stone',
  author: 'J.K Rowling',
  year: 1997,
  isComplete: false,
```
* Nilai timestamp digunakan untuk memastikan keunikan id buku.

**2. Memiliki Dua Rak Buku:**
- Bookshelf Apps memiliki 2 rak buku: **"Belum selesai dibaca"** dan **"Selesai dibaca"**.
- Rak buku "Belum selesai dibaca" hanya menyimpan buku dengan properti *isComplete* bernilai *false*.
- Rak buku "Selesai dibaca" hanya menyimpan buku dengan properti *isComplete* bernilai *true*.

**3. Memindahkan Buku antar Rak:**
<br><p>Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca", dapat dipindahkan di antara keduanya.<p>

**4. Menghapus Data Buku:**
<p>Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca", dapat dihapus.</p>

**5. Manfaatkan localStorage dalam Menyimpan Data Buku:**
<p>Data buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca", dapat bertahan walaupun halaman web ditutup dengan menyimpan data buku pada localStorage.</p>


### Teknologi yang Digunakan:

* HTML
* CSS
* JavaScript

### Cara Menjalankan Aplikasi:
1. Clone repositori ini.
2. Buka file index.html pada browser web Anda.

### Kontribusi:

Kontribusi selalu dipersilakan. Untuk saran atau perbaikan, silakan buat pull request.

### Lisensi:
Dikembangkan oleh <a href="https://linkedin.com/in/daniel-siahaan" style="text-decoration: none;">Daniel Siahaan</a>

![BookShelf App](https://github.com/Nielsiahaan/Dicoding-Web-Pemula/assets/119488265/0375d5bd-c59b-497a-b584-983948d97848)

![BookShelf App](https://github.com/Nielsiahaan/Dicoding-Web-Pemula/assets/119488265/1a36a1c5-32db-49d1-b5b6-fad4f454f674)


