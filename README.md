# Sistem Penerimaan Mahasiswa Baru

## Teknologi Yang Digunakan

1. CodeIgniter 4
2. MySQL DBMS
3. SweetAlert2
4. Datatables
5. jQuery
6. DomPDF
7. AdminLTE 3 (Admin Template)
8. Bizland (Front End Template)

## Installasi

1. Clone repository ini dengan cara `git clone https://github.com/aryadptr/app-pmb.git`
2. Masuk ke direktori app-pmb
3. Jalankan perintah `composer install`
4. Buat database baru dengan nama `app_pmb`
5. Import file `app_pmb.sql` ke database yang telah dibuat
6. Copy file `.env.example` menjadi `.env`
7. Ubah konfigurasi database di file `.env` sesuai dengan database yang telah dibuat
8. Jalankan perintah `php spark serve`
9. Buka browser dan ketikkan `http://localhost:8080`