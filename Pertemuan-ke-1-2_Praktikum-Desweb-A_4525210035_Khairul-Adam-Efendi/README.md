# Penulis

Dibuat oleh Khairul Adam Efendi, mahasiswa Teknik Informatika, Universitas Pancasila.

NIM: 4525210035 | Kelas: A

# Profil UKM PhotoUP Universitas Pancasila

Halaman web statis sederhana yang saya buat menggunakan HTML untuk memperkenalkan UKM PhotoUP Universitas Pancasila (Photo UP KMUP). Halaman ini berisi profil UKM, program kegiatan fotografi, informasi keanggotaan, serta kontak dan media sosial yang berkaitan dengan Universitas Pancasila.

## Deskripsi Singkat

Proyek ini saya buat untuk menerapkan dasar-dasar HTML, seperti struktur dokumen, heading, paragraf, gambar, list, link, dan navigasi antarbagian dalam satu halaman. Melalui halaman ini, saya ingin memperkenalkan PhotoUP sebagai wadah bagi mahasiswa untuk mengembangkan minat dan bakat di bidang fotografi.

## Struktur Halaman

- **Header**: judul "UKM PhotoUP Universitas Pancasila" menggunakan tag `<h1>`.
- **Navigasi**: tautan anchor menggunakan tag `<nav>` dan `<a href="#...">` yang membawa pengguna ke bagian Profil, Kegiatan, Keanggotaan, dan Kontak.
- **Profil UKM**: menampilkan logo menggunakan tag `<img>` dengan atribut `alt` dan `width`, serta paragraf yang menjelaskan PhotoUP dan bidang kegiatannya. Teks tertentu ditebalkan menggunakan `<strong>` dan dimiringkan menggunakan `<em>`.
- **Program Kegiatan**: daftar tidak berurutan menggunakan `<ul>` dengan sub-daftar bersarang, meliputi belajar fotografi, praktik fotografi, pengolahan foto, serta sharing dan diskusi fotografi.
- **Keanggotaan**: menjelaskan informasi umum mengenai kesempatan bergabung dengan PhotoUP dan tahapan untuk mencari informasi pendaftaran. Tahapannya ditampilkan menggunakan ordered list `<ol>`.
- **Kontak & Media Sosial**: menyediakan tautan ke website Universitas Pancasila, halaman informasi UKM, Instagram, dan pencarian kanal YouTube PHOTOUP94.
- **Footer**: menampilkan pernyataan hak cipta menggunakan simbol `&copy;`.

## Tag HTML yang Digunakan

| Tag | Fungsi |
| --- | --- |
| `<!DOCTYPE html>` | Menentukan bahwa dokumen menggunakan HTML5. |
| `<html lang="id">` | Elemen root dengan bahasa Indonesia. |
| `<head>`, `<meta>`, `<title>` | Mengatur informasi dokumen, encoding UTF-8, dan judul tab browser. |
| `<h1>` dan `<h2>` | Membuat judul dan subjudul halaman. |
| `<p>` | Membuat paragraf. |
| `<nav>` dan `<a>` | Membuat navigasi, tautan internal, dan tautan eksternal. |
| `<img>` | Menampilkan logo UKM menggunakan atribut `src`, `alt`, dan `width`. |
| `<ul>`, `<ol>`, dan `<li>` | Membuat daftar tidak berurutan, daftar berurutan, dan sub-daftar. |
| `<strong>` dan `<em>` | Memberikan penekanan berupa teks tebal dan teks miring. |
| `<br>` | Membuat perpindahan baris pada bagian kontak. |
| `&amp;` dan `&copy;` | Menampilkan simbol ampersand (&) dan simbol hak cipta (©). |

## Cara Menjalankan

1. Simpan kode HTML dengan nama `index.html` atau nama file lain yang diinginkan.
2. Pastikan file logo tersedia sesuai path pada atribut `src` di tag `<img>`. Jika menggunakan folder `img`, susunan folder dapat dibuat seperti berikut:

   ```text
   Pertemuan ke-2/
   ├── index.html
   └── img/
       └── photoup.jpg
   ```

3. Gunakan path relatif `img/photoup.jpg` pada atribut `src` jika file HTML berada di folder utama proyek.
4. Buka file HTML menggunakan browser seperti Google Chrome, Microsoft Edge, atau Mozilla Firefox.

## Hasil Run

<img width="1920" height="1080" alt="Output Tugas 2" src="https://github.com/user-attachments/assets/8127024d-3305-435a-a0b3-eb7f5adc0775" />

