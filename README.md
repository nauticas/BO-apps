# Nauticas KRS-Online
Merupak aplikasi yang dibangun mengunakan framework Laravel yang memiliki fungsi untuk manajemen KRS mahasiswa, jadwal kuliah, ruang kelas, dosen, mahasiswa, matakuliah, perwalian, sampai dengan penilaian mahasiswa. Framework Laravel yang digunakan versi 5.3 dengan minimal PHP versi 5.6, dimaksudkan menggunakan versi ini adalah masih banyak server yang ada atau penyedia hosting masih menggunakan PHP Versi 5.6.

## Kebutuhan
1. Apache
2. PHP>=5.6
3. MySql

## Instalasi
1. Download atau *clone* dari github dengan perintah :
```
git clone https://github.com/nauticas/krs.git
```  
2. Extarct file yang telah di download/clone ke direktori kerja
3. Edit file .env, sesuaikan konfigurasi database pada baris berikut:
```
DB_CONNECTION=mysql
DB_HOST=localhost
DB_PORT=3306
DB_DATABASE=nama_database
DB_USERNAME=username_database
DB_PASSWORD=password_database
```
4. Jalankan perintah sebagai berikut untuk membuat tabel dan data pada database
```
php artisan migrate
```
5. Tunggu sampai proses migrasi database selesai
6. Akses aplikasi menggunakan browser kemudian login menggunakan akses di bawah ini:
```
# Admin
username = admin
password = admin
# Dosen
username = D226
password = D226
# Mahasiswa
username = 82094
password = 82094
```

## Developer
### Dhitya Pamungkas [155410007]
### Arif Riyadi [1555410098]
