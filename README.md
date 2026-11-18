# Katalog Produk JavaFX & SQLite

Aplikasi desktop berbasis **JavaFX** dan **SQLite** untuk mengelola data katalog produk dengan fitur CRUD (Tambah, Lihat, Edit, dan Hapus produk).

## Fitur

- Tambah produk
- Lihat daftar produk
- Edit produk
- Hapus produk

## Prasyarat

- JDK (versi sesuai konfigurasi `pom.xml`)
- Apache Maven
- Apache NetBeans IDE (opsional, jika ingin menjalankan lewat IDE)
- Koneksi internet saat pertama kali menjalankan, agar Maven dapat mengunduh dependensi JavaFX dan SQLite JDBC

## Cara Menjalankan Aplikasi

### Lewat Apache NetBeans

1. Buka proyek **KatalogProduk** melalui menu **File > Open Project**.
2. Pastikan koneksi internet aktif saat pertama kali menjalankan proyek agar Maven mengunduh dependensi JavaFX dan SQLite JDBC.
3. Klik kanan pada proyek **KatalogProduk** > **Run Maven** > **Goals...**, ketik `javafx:run`, lalu klik **OK**.

### Lewat Terminal

Masuk ke folder proyek, lalu jalankan:

```bash
mvn clean javafx:run
```

## Screenshot Aplikasi

<img width="1230" height="885" alt="SS Katalog" src="https://github.com/user-attachments/assets/6b61c0df-0f83-4e76-b200-7648e77aac9e" />
