---

# Laravel Multi-Auth Example

Ini adalah proyek contoh Laravel dengan fitur multi-auth yang dibangun menggunakan Laravel. Proyek ini menyediakan autentikasi untuk dua jenis pengguna: pengguna biasa dan administrator.

## Instalasi

1. Pastikan Anda telah menginstal PHP, Composer, dan MySQL di komputer Anda.
2. Clone repositori ini ke komputer Anda.
3. Salin file `.env.example` menjadi `.env` dan atur konfigurasi database sesuai dengan pengaturan Anda.
4. Instal dependensi dengan menjalankan perintah `composer install`.
5. Jalankan migrasi untuk membuat tabel database dengan perintah `php artisan migrate`.
6. Anda juga dapat menjalankan *seeder* untuk membuat data dummy dengan perintah `php artisan db:seed`.

## Penggunaan

1. Untuk mengakses aplikasi, jalankan server Laravel dengan perintah `php artisan serve`.
2. Buka browser dan arahkan ke `http://localhost:8000` untuk melihat halaman utama aplikasi.
3. Pengguna akan dapat melakukan pendaftaran, masuk, dan keluar sesuai dengan peran mereka (pengguna biasa atau administrator).
4. Pengguna dengan peran administrator dapat mengakses fitur tambahan yang tidak tersedia bagi pengguna biasa.

Pastikan untuk mengubah atau menambahkan informasi yang diperlukan sesuai dengan kebutuhan proyek Anda.
