# Telkom University Company Profile - Praktikum

Proyek simulasi untuk mempelajari HTML, CSS, PHP native, MySQL/MariaDB, dan Git.

Nama: Najwa Ignatia Sulhani
NIM: 109062500061

Perubahan ini dibuat dari simulasi Laptop A.
Perubahan ini dibuat dari simulasi Laptop B.

## Menjalankan secara lokal

1. Salin folder proyek ke folder `htdocs` XAMPP / `www` Laragon.
2. Start Apache dan MySQL.
3. Import `database/telkom_profile.sql` melalui HeidiSQL atau phpMyAdmin.
4. Buka `http://localhost/telkom-company-profile/`.

> Catatan: seluruh konten institusi bersifat simulasi untuk pembelajaran.

## Dokumentasi Merge Conflict

Conflict terjadi pada `includes/header.php`. Branch `conflict-navbar` mengubah label menu Profil menjadi "Tentang Kami", sedangkan `main` mengubahnya menjadi "Tentang Kampus" pada baris yang sama, sehingga Git tidak bisa menggabungkan otomatis. Saya membuka file, memilih teks final "Profil", menghapus marker conflict (`<<<<<<<`, `=======`, dan `>>>>>>>`), lalu menjalankan `git add` dan `git commit`.

## Riwayat Praktikum Git

```text
* f87590e (HEAD -> main, origin/main, origin/HEAD) Revert "docs: baris uji revert"
* f65d4a3 docs: baris uji revert
* f2d4d67 Merge branch 'main' of https://github.com/bbulcumcum/telkom-company-profile-109062500061 # Please enter a commit message to explain why this merge is necessary, # especially if it merges an updated upstream into a topic branch. # Lines starting with '#' will be ignored, and an empty message aborts the commit.
|\  
| * 4e0a341 docs: tambah catatan kedua dari Laptop B
| * d8fb0de docs: tambah catatan dari Laptop A
|/  
* 18c8f4e docs: perbarui README dari Laptop B
* 57dd374 feat: tambahkan footer bersama
* 21b2062 feat: hubungkan database dan tampilkan program studi
*   c6a425b merge: selesaikan conflict navbar
|\  
| * d315d03 (conflict-navbar) feat: ubah label profil pada branch conflict
* | ec1a211 style: ubah label profil pada main
|/  
* f829c55 feat: tambahkan form admin lokal untuk berita
* 9daa554 feat: simpan pesan kontak ke database
* c0434c9 feat: tambahkan daftar dan detail berita
* 8204321 feat: tambahkan layout dasar dan stylesheet
* 252c3f7 feat: tambahkan layout dasar dan stylesheet
* 70aab8f chore: inisialisasi project dan dokumentasi awal