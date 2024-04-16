# perpustakaan
Sistem Informasi Manajemen Perpustakaan Sederhana ini adalah -seperti namanya- sebuah sistem sederhana untuk mengelola perpustakaan dari manajemen pustakawan, anggota, buku, hingga peminjaman buku yang dibuat dengan sesederhana mungkin agar mudah digunakan.
# kebutuhan sistem
- PHP 8.1+
- Composer
# proses instalasi
- Fork repositori ini terlebih dahulu. 
- Kemudian clone ke dalam komputer Anda. git clone url-repositori
- Masuk ke dalam folder projek. cd perpustakaan
- Install dependencies. composer install
- Salin file env. cp .env.example .env
- Sesuaikan nilai pada env, misalnya kredensial database
- Masukkan data. php artisan migrate --seed
- Jalankan projek. php artisan serve
- Buka di browser http://localhost:8000
