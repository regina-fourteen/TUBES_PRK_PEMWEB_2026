# SehatIn - Portal Informasi dan Edukasi Kesehatan

## 1. Deskripsi Proyek

SehatIn merupakan platform berbasis web yang dikembangkan sebagai portal pusat informasi edukasi kesehatan populer dan tips pola hidup sehat. Aplikasi ini bertujuan untuk memudahkan masyarakat dalam memperoleh informasi kesehatan yang informatif, mudah dipahami, dan dapat diakses secara praktis.

SehatIn menyediakan berbagai informasi kesehatan melalui artikel, kategori, dan tips kesehatan. Selain itu, terdapat halaman administrator yang digunakan untuk mengelola konten agar informasi yang ditampilkan pada website dapat diperbarui secara terstruktur.

## 2. Fitur Aplikasi

### A. Fitur Pengunjung

- **Beranda:** Menampilkan halaman utama dan informasi kesehatan.
- **Artikel Kesehatan:** Menampilkan berbagai artikel edukasi kesehatan.
- **Kategori Artikel:** Mengelompokkan artikel berdasarkan kategori tertentu.
- **Tips Kesehatan:** Menampilkan tips mengenai pola hidup sehat.
- **Detail Artikel:** Menampilkan isi artikel secara lengkap.
- **Pencarian Artikel:** Membantu pengunjung menemukan informasi kesehatan.

### B. Fitur Administrator

- **Login dan Logout:** Mengatur akses administrator ke halaman pengelolaan.
- **Dashboard Admin:** Menampilkan ringkasan informasi pengelolaan website.
- **Manajemen Artikel:** Menambah, melihat, mengubah, dan menghapus artikel.
- **Manajemen Kategori:** Mengelola kategori artikel kesehatan.
- **Manajemen Tips:** Mengelola informasi tips kesehatan.

## 3. Teknologi yang Digunakan

Pengembangan aplikasi SehatIn menggunakan beberapa teknologi berikut:

| Teknologi | Kegunaan |
|---|---|
| PHP Native | Bahasa pemrograman sisi server |
| MySQL | Sistem manajemen basis data |
| HTML5 | Struktur halaman website |
| CSS3 | Mengatur tampilan website |
| JavaScript | Menambahkan interaksi pada halaman |
| Bootstrap | Membantu pengembangan antarmuka responsif |
| Bootstrap Icons | Menyediakan ikon antarmuka |
| XAMPP / Laragon | Lingkungan pengembangan lokal |
| Apache | Web server untuk menjalankan aplikasi |

## 4. Persyaratan Sistem

Sebelum menjalankan aplikasi, pastikan perangkat telah memiliki:

- Sistem operasi Windows, Linux, atau macOS.
- PHP dengan versi yang sesuai dengan source code proyek.
- MySQL atau MariaDB.
- Apache Web Server.
- XAMPP atau Laragon.
- Browser seperti Google Chrome, Microsoft Edge, atau Mozilla Firefox.
- Git (opsional, jika menggunakan metode clone repository).

## 5. Instalasi dan Konfigurasi

Ikuti langkah-langkah berikut untuk menjalankan aplikasi SehatIn di lingkungan lokal.

### A. Mengambil Source Code dari GitHub Laboratorium

Source code awal proyek dapat diperoleh melalui repository GitHub Laboratorium Komputer Teknik Informatika Universitas Lampung:

https://github.com/Praktikum-LabKom-TI-Unila/TUBES_PRK_PEMWEB_2026

Terdapat dua cara untuk mengambil source code.

**Cara 1: Menggunakan Git Clone**

1. Pastikan Git telah terinstal pada komputer.
2. Buka Command Prompt, Git Bash, atau terminal Visual Studio Code.
3. Jalankan perintah berikut:

   ```bash
   git clone https://github.com/Praktikum-LabKom-TI-Unila/TUBES_PRK_PEMWEB_2026.git
   ```

4. Tunggu hingga proses pengunduhan selesai.
5. Setelah berhasil, akan terbentuk folder `TUBES_PRK_PEMWEB_2026` pada direktori tempat perintah dijalankan.
6. Buka folder tersebut dan cari folder proyek kelompok yang akan digunakan.

**Cara 2: Mengunduh ZIP dari GitHub**

1. Buka repository GitHub Laboratorium melalui tautan berikut:

   https://github.com/Praktikum-LabKom-TI-Unila/TUBES_PRK_PEMWEB_2026

2. Klik tombol **Code**.
3. Pilih **Download ZIP**.
4. Tunggu hingga proses pengunduhan selesai.
5. Ekstrak file ZIP yang telah diunduh.
6. Buka folder hasil ekstraksi dan cari folder proyek kelompok.

### B. Memindahkan Folder Proyek ke Direktori Web Server

Setelah mendapatkan source code, pindahkan folder proyek kelompok ke direktori web server agar aplikasi dapat dijalankan melalui browser.

Lokasi direktori menyesuaikan aplikasi web server yang digunakan:

**Jika menggunakan XAMPP:**

Pindahkan folder proyek ke:

```text
C:\xampp\htdocs\
```

Contoh:

```text
C:\xampp\htdocs\kelompok_12\
```

**Jika menggunakan Laragon:**

Pindahkan folder proyek ke:

```text
C:\laragon\www\
```

Contoh:

```text
C:\laragon\www\kelompok_12\
```

Pastikan folder proyek yang dipindahkan merupakan folder utama aplikasi yang berisi file `index.php`, bukan folder repository GitHub secara keseluruhan.

### C. Menjalankan Web Server

1. Buka XAMPP Control Panel atau Laragon.
2. Aktifkan layanan Apache.
3. Aktifkan MySQL.
4. Pastikan kedua layanan berhasil berjalan.

### D. Membuat Database

1. Buka browser.
2. Akses phpMyAdmin melalui alamat:

   ```text
   http://localhost/phpmyadmin
   ```

3. Buat database baru sesuai nama database yang digunakan pada konfigurasi aplikasi.
4. Buka folder `database` pada proyek.
5. Cari file SQL yang disediakan.
6. Pilih database yang telah dibuat.
7. Klik menu **Import**.
8. Pilih file SQL tersebut, kemudian klik **Import** atau **Go**.
9. Tunggu hingga proses import selesai.

### E. Mengatur Koneksi Database

Sesuaikan konfigurasi database pada file koneksi aplikasi yang berada di folder `config`.

Pastikan informasi koneksi sesuai dengan konfigurasi MySQL lokal.

Contoh konfigurasi:

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "nama_database";
```

Sesuaikan nilai `nama_database` dengan nama database yang telah dibuat sebelumnya.

Pastikan juga username dan password sesuai dengan konfigurasi MySQL pada perangkat masing-masing.

### F. Menjalankan Aplikasi

Setelah seluruh proses instalasi selesai, buka browser dan akses alamat berikut:

Jika menggunakan folder `kelompok_12`:

```text
http://localhost/kelompok_12/
```

Apabila halaman utama SehatIn berhasil ditampilkan, aplikasi sudah dapat digunakan.

## 6. Panduan Penggunaan

### A. Penggunaan sebagai Pengunjung

1. Buka aplikasi SehatIn melalui browser.
2. Pengunjung akan diarahkan ke halaman beranda.
3. Pilih menu artikel untuk melihat informasi kesehatan.
4. Pilih kategori untuk menemukan artikel berdasarkan topik kesehatan.
5. Buka salah satu artikel untuk membaca informasi secara lengkap.
6. Akses halaman tips kesehatan untuk memperoleh informasi mengenai pola hidup sehat.

### B. Penggunaan sebagai Administrator

1. Buka halaman login administrator melalui menu atau alamat halaman admin yang tersedia pada aplikasi.
2. Masukkan username dan password administrator.
3. Setelah berhasil login, administrator akan diarahkan ke dashboard.
4. Gunakan menu pengelolaan untuk menambah, mengubah, melihat, atau menghapus artikel.
5. Kelola kategori artikel sesuai kebutuhan.
6. Kelola tips kesehatan yang akan ditampilkan kepada pengunjung.
7. Setelah selesai, gunakan fitur logout untuk mengakhiri sesi administrator.

## 7. Struktur Direktori

Berikut gambaran struktur direktori utama aplikasi SehatIn:

```text
kelompok_12/
│
├── admin/
│   └── Halaman dan fitur administrator
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── config/
│   └── Konfigurasi koneksi database
│
├── database/
│   └── File database SQL
│
├── includes/
│   └── Komponen pendukung halaman
│
├── uploads/
│   └── File yang diunggah
│
├── index.php
└── README.md
```

*Catatan: Struktur di atas merupakan gambaran umum. Nama file dan subfolder dapat menyesuaikan struktur aktual pada source code proyek.*

## 8. Pemecahan Masalah

Beberapa kendala yang mungkin ditemukan ketika menjalankan aplikasi:

**1. Halaman tidak dapat dibuka**

- Pastikan Apache telah berjalan.
- Periksa kembali lokasi folder proyek.
- Pastikan URL pada browser sesuai dengan nama folder proyek.

**2. Koneksi database gagal**

- Pastikan MySQL telah aktif.
- Periksa nama database, username, dan password.
- Pastikan database telah dibuat dan file SQL berhasil diimpor.

**3. Tampilan website tidak sempurna**

- Pastikan seluruh file CSS, JavaScript, dan gambar tersedia.
- Periksa kembali lokasi folder assets.
- Lakukan refresh halaman browser.

**4. Tidak dapat login sebagai administrator**

- Pastikan akun administrator tersedia pada database.
- Periksa username dan password yang digunakan.
- Pastikan proses autentikasi dan koneksi database berjalan dengan baik.

## 9. Catatan Pengembangan

Aplikasi SehatIn dikembangkan menggunakan PHP Native dan MySQL tanpa menggunakan framework pengembangan aplikasi seperti Laravel, CodeIgniter, React, Vue, maupun Next.js.

Bootstrap dan Bootstrap Icons digunakan sebagai pendukung tampilan antarmuka. Seluruh proses pengolahan data dan logika aplikasi dikembangkan menggunakan PHP Native dan JavaScript sesuai kebutuhan proyek.

---

**SehatIn - Portal Pusat Informasi Edukasi Kesehatan Populer dan Tips Pola Hidup Sehat**

Dikembangkan sebagai proyek Tugas Besar Praktikum Pemrograman Web.