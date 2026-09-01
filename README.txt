DIMSUM BAKAR NAGIH.IN — WEBSITE STATIS
========================================

ISI FOLDER
----------
index.html   -> struktur & isi teks website
style.css    -> semua tampilan (warna, font, layout)
assets/      -> semua gambar yang dipakai website

GANTI GAMBAR
------------
Cukup timpa (replace) file di folder assets/ dengan foto baru,
PAKAI NAMA FILE YANG SAMA supaya tidak perlu edit index.html:

  assets/logo.jpg   -> logo di pojok kiri atas & footer
  assets/hero.jpg   -> foto lingkaran di halaman Beranda
  assets/about.jpg  -> foto di bagian Tentang
  assets/menu.jpg   -> foto produk di bagian Menu

Kalau mau pakai nama file / format lain (mis. logo.png), ubah juga
rujukannya di index.html (cari src="assets/logo.jpg" lalu ganti).

Untuk hasil rapi, foto hero/about/menu sebaiknya rasio persegi (1:1)
atau mendekati, karena beberapa ditampilkan bulat/dipotong otomatis.

GANTI TEKS
----------
Setiap teks di index.html punya dua versi:
  data-id="...versi Indonesia..."
  data-en="...versi Inggris..."
Ubah keduanya di tempat yang sama supaya toggle bahasa (tombol ID/EN
di pojok kanan atas) tetap konsisten.

Bagian yang masih placeholder dan sebaiknya diganti duluan:
  - Berita (3 contoh kabar)
  - Tim (kartu kedua "Timmu di sini")
  - Menu (harga/varian kalau berubah)

CARA LIHAT / PUBLISH
---------------------
- Buka index.html langsung di browser untuk cek tampilan.
- Untuk online-kan: upload seluruh folder ini (index.html, style.css,
  assets/) ke Netlify, Vercel, GitHub Pages, atau hosting statis lain.
