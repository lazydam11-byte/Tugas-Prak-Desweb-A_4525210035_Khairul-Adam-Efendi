# Tugas Praktikum Pertemuan 4 - Desain Web

**Nama:** Khairul Adam Efendi
**NPM:** 4525210035
**Kelas:** A

## Tugas Individu

Membangun ulang halaman landing page Arunika Studio menjadi dua file (`index.html` dan `style.css`) dengan box model, minimal dua class reusable, dan satu media query di bawah 768px.

## File

| File | Keterangan |
|---|---|
| `index.html` | Struktur halaman (header, hero, tiga layanan, footer) |
| `style.css` | CSS |
| `img/logo.jpg` | Logo Arunika Studio |

## Yang Dipakai

- **Box model:** `box-sizing: border-box`, `padding`, `border`, `margin` pada `.container`, `.section`, dan `.card`.
- **Card:** tepat 3 card (Logo & Branding, Desain Media Sosial, Website Landing Page); 3 kolom di desktop, 1 kolom di mobile.
- **Class reusable:** `.container`, `.section`, `.card`, `.button`.
- **Media query:** `@media (max-width: 767px)` untuk layar di bawah 768px.

## Screenshot

| Biodata |
<img width="1919" height="1079" alt="Screenshot 2026-11-03 074426" src="https://github.com/user-attachments/assets/49d89fda-80a3-49cd-9905-8b018754d0ea" />

| Arunika Studio |
<img width="1919" height="1079" alt="Screenshot 2026-11-03 074535" src="https://github.com/user-attachments/assets/ed265bb8-6c7b-4499-bda8-d712f35d15c1" />

## Ringkasan Perubahan, Masalah, dan Solusi

Pada tugas ini saya membangun ulang halaman Arunika Studio menjadi dua file terpisah, yaitu `index.html` untuk struktur dan `style.css` untuk tampilan. Semua gaya dikumpulkan di satu file yang tersusun per bagian, lalu warnanya diganti. Box model saya terapkan lewat `padding`, `border`, `margin`, dan `box-sizing: border-box` supaya ukuran elemen lebih mudah dihitung. Saya juga memakai class reusable seperti `.container`, `.section`, `.card`, dan `.button` sehingga satu aturan bisa dipakai berulang tanpa menulis ulang kode.

Masalah yang muncul adalah kode CSS yang masih memuat aturan tidak terpakai seperti `.hero-sun` dan belum mengatur ukuran gambar logo, sehingga tampilannya tidak terkendali. Selain itu, tiga card layanan terlalu sempit kalau tetap berjajar di layar ponsel, dan tombol di dalam card tidak sejajar karena panjang teks setiap card berbeda. Solusinya, semua gaya dikumpulkan di satu `style.css` yang tersusun per bagian, gambar hero diatur dengan `object-fit`, dan card memakai flexbox. Lalu saya menambahkan satu media query pada lebar di bawah 768px yang mengubah hero menjadi vertikal dan tiga card menjadi satu kolom.

Studi kasus Arunika Studio saya rapikan dengan menerapkan box model lewat `padding`, `border`, `margin`, dan `box-sizing: border-box`, serta class reusable `.container`, `.section`, `.card`, dan `.button`. Tombol di dalam card dibuat rata di dasar card, dan tiga card berubah menjadi satu kolom pada layar kecil.
