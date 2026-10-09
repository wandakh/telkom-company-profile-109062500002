# Telkom University Company Profile - Praktikum 


Perubahan ini dibuat dari simulasi Laptop B.

## Riwayat Praktikum Git

### Penjelasan Singkat Penyelesaian Merge Conflict
Selama proses kolaborasi (simulasi Laptop A dan Laptop B), terjadi *merge conflict* pada file `README.MD`. Konflik ini terjadi karena kedua repositori lokal mengubah baris yang sama sebelum dilakukan penggabungan (*pull*). 

Langkah penyelesaian yang saya lakukan:
1. Membuka file `README.MD` di editor (VS Code).
2. Mencari dan menghapus *marker* konflik yang dibuat oleh Git 
3. Menggabungkan dan merapikan teks menjadi satu versi final yang benar, lalu menyimpan file tersebut.
4. Menjalankan perintah `git add README.MD` dan `git commit -m "merge: selesaikan conflict README antara Laptop A dan B"` untuk menyelesaikan proses penggabungan.

### Output Riwayat Git
```text
*   77dcc35 (HEAD -> main, tag: v1.0.0, origin/main, origin/HEAD) merge: selesaikan conflict README antara Laptop A dan B
|\  
| * bb6ae52 docs: perbarui README dari Laptop B
* | 8cc4933 docs: perbarui README dari Laptop A
|/  
* ab38c80 merge: selesaikan conflict navbar
*   8ad2538 Merge branch 'conflict-navbar'
|\  
| * f25b22a (conflict-navbar) feat: ubah label profil pada branch conflict
* | f091672 style: ubah label profil pada main
|/  
* c3d4b8c feat: tambahkan informasi fokus pembelajaran
* e7c68ab feat: tambahkan form admin lokal untuk berita
* fc08739 feat: simpan pesan kontak ke database
* f299068 feat: tambahkan daftar dan detail berita
* 27af1a8 feat: hubungkan database dan tampilkan program studi
* 1043d2e feat: tambahkan layout dasar dan stylesheet
* ff5d9b4 chore: inisialisasi project dan dokumentasi awal

Project simulasi HTML, CSS, PHP native, MySQL/MariaDB, dan Git. D


Project simulasi HTML, CSS, PHP native, MySQL/MariaDB, dan Git. D

