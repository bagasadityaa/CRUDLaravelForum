# Laravel Forum Berita CRUD
Hai! Project CRUD Laravel Forum Berita ini adalah aplikasi forum berita sederhana yang dibuat dengan menggunakan framework Laravel. Aplikasi ini memiliki fitur CRUD (Create, Read, Update, Delete) untuk berita pada forum.

## Fitur Utama
Aplikasi CRUD ini memiliki fitur utama sebagai berikut: 
1. Menampilkan daftar berita pada forum
2. Menampilkan detail berita.
3. Membuat berita baru.
4. Mengedit berita yang sudah ada
5. Menghapus berita 

## Getting Started
Untuk menjalankan aplikasi ini, pastikan komputer anda terinstal PHP 8.0, MySQL, dan Composer. Lakukan langkah-langkah berikut untuk menginstal aplikasi:
1. Clone repositori ini ke komputer Anda dengan menjalankan perintah berikut di terminal: 
* git 
```sh
git clone github.com/bagasadityaa/CRUDUserAndroidStudioJava.git
```

2. Masuk ke direktori aplikasi dengan menjalankan perintah berikut di terminal:
* git
```sh
cd CRUDLaravelForum
```

3. Install dependencies yang dibutuhkan oleh aplikasi dengan menjalankan perintah berikut di terminal:
* terminal
```sh
composer install
```

4. Salin file .env.example menjadi file .env dengan menjalankan perintah berikut di terminal:
* terminal
```sh
cp .env.example .env
```

5. Generate key aplikasi dengan menjalankan perintah berikut di terminal:
* terminal
```sh
php artisan key:generate
```

6. Konfigurasi database di file .env dengan menyesuaikan nilai DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, dan DB_PASSWORD sesuai dengan pengaturan database.

7. Jalankan migrasi database dengan menjalankan perintah berikut di terminal:
* terminal
```sh
php artisan migrate
```

8. Jalankan aplikasi dengan menjalankan perintah berikut di terminal:
*terminal 
```sh
php artisan serve
```
aplikasi akan berjalan di 'http://localhost:8000'

## Kontak
Bagas Aditya - [@bagas_adtyaa](https://www.instagram.com/bagas_adtyaa/)
