# Telkom University Company Profile - Praktikum

Proyek simulasi untuk mempelajari HTML, CSS, PHP native, MySQL/MariaDB, dan Git.
## Menjalankan secara lokal
1. Salin folder proyek ke `htdocs` XAMPP.
2. Start Apache dan MySQL.
3. Import `database/telkom_profile.sql` melalui phpMyAdmin.
4. Buka `http://localhost/telkom-company-profile/`.

## Penyelesaian Merge Conflict
Conflict terjadi pada `includes/header.php` karena branch `main` dan `conflict-navbar` mengubah label menu Profil secara berbeda. Saya memilih label "Profil", menghapus tanda conflict, lalu menjalankan `git add` dan `git commit`.
## Riwayat Praktikum Git

```
* d7b7153 (HEAD -> main, tag: v1.0.0, origin/main, origin/HEAD) Revert "docs: tambah catatan dari Laptop A"
*   7afacfc Merge branch 'main' of https://github.com/kaylanaur/telkom-company-profile-109062500108
|\
| * 7e85b7b docs: tambah catatan simulasi push ditolak dari Laptop B
* | 13984ad docs: tambah catatan dari Laptop A
|/
* 2ae1fbf docs: perbarui README dari Laptop B
*   7766299 merge: selesaikan conflict navbar
|\
| * 2421c29 (conflict-navbar) feat: ubah label profil pada branch conflict
* | 0ea6ec6 style: ubah label profil pada main
|/
* a686d8e feat: tambahkan informasi fokus pembelajaran
* e96ef8e feat: tambahkan form admin lokal untuk berita
* b4b4905 feat: simpan pesan kontak ke database
* 4cbc35d feat: tambahkan daftar dan detail berita
* be4471c feat: hubungkan database dan tampilkan program studi
* 7860519 feat: tambahkan layout dasar dan stylesheet
* ab29838 chore: inisialisasi project dan dokumentasi awal
```