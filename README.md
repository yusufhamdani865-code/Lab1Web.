# Praktikum 1 – HTML Dasar

## Identitas Mahasiswa

**Nama:** Yusuf Hamdani
**NIM:** 312510049
**Program Studi:** Teknik Informatika

---

## 1. Tujuan Praktikum

Praktikum ini bertujuan untuk mempelajari dasar-dasar HTML serta memahami struktur dasar dokumen HTML. Pada praktikum ini dibuat sebuah halaman profil mahasiswa dengan menggunakan beberapa elemen HTML dasar, seperti heading, paragraf, formatting teks, gambar, hyperlink, unordered list, ordered list, dan komentar.

---

## 2. Alat yang Digunakan

* Visual Studio Code
* Web Browser
* GitHub

---

## 3. Langkah-Langkah Praktikum

### 3.1 Membuat Struktur Dasar HTML

Langkah pertama adalah membuat dokumen HTML menggunakan struktur dasar HTML5. Struktur tersebut terdiri dari `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, dan `<body>`.

Struktur dasar ini digunakan sebagai kerangka utama untuk membuat halaman web.

![SS1 - membuat struktur dasar HTML](Screenshot/ss%201.png)

---

### 3.2 Membuat Judul dan Data Diri

Selanjutnya dibuat judul halaman menggunakan elemen `<h1>` dan bagian data diri menggunakan `<h2>` serta `<p>`.

Data diri yang ditampilkan meliputi nama, NIM, dan program studi. Elemen `<strong>` digunakan untuk memberikan penekanan pada informasi tertentu, sedangkan `<i>` digunakan untuk membuat teks menjadi miring.

![SS2 - Judul dan Data Diri](Screenshot/ss%202.png)

---

### 3.3 Menambahkan Gambar dan Hyperlink

Pada tahap ini ditambahkan gambar profil menggunakan elemen `<img>`. Gambar disimpan di dalam folder `images`.

Selain itu, ditambahkan hyperlink menggunakan elemen `<a>` untuk menghubungkan halaman dengan website lain.

Contoh penggunaan gambar:

```html
<img src="images/profil.jpg" width="200" alt="Foto profil Yusuf Hamdani">
```

![SS3 - Gambar dan Hyperlink](Screenshot/ss%203.png)

---

### 3.4 Membuat Keahlian dan Target Belajar

Selanjutnya dibuat bagian **Keahlian** menggunakan unordered list `<ul>`. Setiap keahlian dituliskan menggunakan elemen `<li>`.

Kemudian dibuat bagian **Target Belajar** menggunakan ordered list `<ol>` sehingga target belajar ditampilkan dalam bentuk daftar yang berurutan.

Contoh penggunaan unordered list:

```html
<ul>
    <li>HTML</li>
    <li>Java</li>
    <li>Python</li>
</ul>
```

Contoh penggunaan ordered list:

```html
<ol>
    <li>Menguasai HTML</li>
    <li>Menguasai CSS</li>
    <li>Mempelajari JavaScript</li>
</ol>
```

![SS4 - Keahlian dan Target Belajar](Screenshot/ss%204.png)

---

### 3.5 Hasil Akhir Praktikum

Setelah seluruh elemen HTML selesai dibuat, halaman profil mahasiswa dijalankan melalui web browser.

Hasil akhir menampilkan judul, data diri, gambar profil, hyperlink, daftar keahlian, dan target belajar dalam satu halaman web.

![SS5 - Hasil Akhir](Screenshot/ss%205.png)

---

## 4. Hasil Praktikum

Hasil dari praktikum ini adalah sebuah halaman web sederhana berupa **Profil Mahasiswa** menggunakan HTML dasar.

Elemen HTML yang digunakan dalam halaman tersebut meliputi:

* Struktur dasar HTML5
* Heading `<h1>` dan `<h2>`
* Paragraf `<p>`
* Formatting teks `<strong>` dan `<i>`
* Gambar `<img>`
* Hyperlink `<a>`
* Unordered list `<ul>`
* Ordered list `<ol>`
* Komentar HTML `<!-- komentar -->`

---

## 5. Kesimpulan

Pada Praktikum 1 HTML Dasar, telah dipelajari struktur dasar dokumen HTML serta penggunaan beberapa elemen HTML untuk membuat halaman web sederhana.

Melalui praktikum ini, saya memahami penggunaan HTML untuk menyusun isi halaman web, seperti judul, paragraf, gambar, hyperlink, dan daftar. Hasil praktikum berupa halaman profil mahasiswa yang menggabungkan beberapa elemen HTML dasar dalam satu halaman.

---

## 6. Repository GitHub

Repository praktikum ini dibuat menggunakan GitHub dengan nama **Lab1Web**.

Repository digunakan untuk menyimpan file HTML, gambar, screenshot dokumentasi, dan README sebagai dokumentasi praktikum.
