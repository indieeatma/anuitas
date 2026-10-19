# LARAS — Website Pembelajaran Anuitas

Versi ini disiapkan untuk publikasi sebagai situs statis melalui GitHub Pages, dengan perbaikan kompatibilitas dan pemuatan awal.

## Isi utama
- `index.html` — website utama.
- `LK-Anuitas.pdf` — lembar aktivitas yang dimuat saat bagian terkait dibuka.
- `poster-anuitas/` — poster-poster pembelajaran; poster PNG besar dioptimalkan menjadi JPEG.
- `.nojekyll` — meminta GitHub Pages menyajikan berkas statis tanpa pemrosesan Jekyll.
- `404.html` — halaman bantuan untuk URL yang tidak ditemukan.

## Cara memasang ke GitHub Pages
1. Ekstrak seluruh isi ZIP ini.
2. Buka repositori `indieeatma/anuitas` di GitHub.
3. Unggah **isi folder** ini ke direktori publikasi yang dipilih, bukan folder pembungkusnya. Pastikan `index.html` berada langsung di root jika Pages memakai `main` → `/(root)`.
4. Jika GitHub memberi pilihan, izinkan penggantian berkas lama dengan versi revisi ini.
5. Buka **Settings → Pages**. Untuk publikasi dari branch, pilih branch `main` dan folder `/(root)`, lalu Save.
6. Buka tab **Actions** dan tunggu workflow Pages selesai dengan status berhasil.
7. Kunjungi URL yang ditampilkan di Settings → Pages. Perubahan bisa memerlukan beberapa menit untuk tampil.

## Catatan
- Website ini berupa HTML/CSS/JavaScript statis; tidak membutuhkan Node.js atau proses build.
- Gunakan URL relatif seperti `poster-anuitas/nama-file.jpg` agar aset bekerja di alamat project GitHub Pages.
- Fitur refleksi yang disimpan ke `localStorage` tersimpan hanya di browser/perangkat yang digunakan. Gunakan tombol unduh untuk menyimpan salinan.
- Pengalaman dapat berbeda tergantung versi browser, koneksi internet, dan dukungan pemutar PDF/video pada perangkat. PDF juga tersedia sebagai berkas yang dapat diunduh dari halaman website.
