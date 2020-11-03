# Sistem-Informasi-Keuangan

## Cara Install
### 1. Clone project
` git clone https://github.com/Qorthony/Sistem-Informasi-Keuangan.git `
### 2. Composer Install
- buka terminal/cli pada direktori project
- kemudian ketik perintah : ` composer install `
### 3. Buat database
- buka phpmyadmin
- buat database baru
### 4. Setting ENV
- buka project pada text editor
- duplikasi file env
- rename file env menjadi .env
- buka file .env
- hapus tanda hashtag pada CI_ENVIRONMENT dan ganti nilai nya menjadi development
- hapus tanda hashtag mulai dari database.default.hostname hingga database.default.DBDriver
- setting nilai database, username, dan password sesuai yang ada di perangkatmu. jika tidak menggunakan password cukup kosongi bagian password
### 5. Migrate Database
- buka terminal/cli pada direktori project
- ketik perintah : ` php spark migrate `
### 6. Jalankan Program
- buka terminal/cli pada direktori project
- ketik perintah : ` php spark serve `
- buka browser, ketik localhost:8080
