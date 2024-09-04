### 1. **Tag `<html>`**

- **Singkatan:** HTML adalah singkatan dari **HyperText Markup Language**.
- **Definisi:** HTML adalah bahasa markup yang digunakan untuk membuat struktur dasar dan konten dari sebuah halaman web. Tag `<html>` adalah elemen root yang membungkus semua konten dalam dokumen HTML.
- **Fungsi:** Tag ini memberitahu browser bahwa dokumen tersebut adalah dokumen HTML. Semua elemen lain dalam halaman web harus berada di dalam tag `<html>`.

### 2. **Tag `<head>`**

- **Singkatan:** "Head" adalah bagian "kepala" dari dokumen HTML.
- **Definisi:** Elemen `<head>` berfungsi untuk menyimpan metadata dan informasi tentang dokumen, seperti judul halaman (`<title>`), link ke stylesheet (`<link>`), dan skrip (`<script>`).
- **Fungsi:** Konten di dalam `<head>` tidak terlihat oleh pengguna, tetapi penting untuk pengaturan halaman dan interaksi dengan mesin pencari serta pengaturan lainnya.

### 3. **Tag `<body>`**

- **Singkatan:** "Body" adalah bagian "tubuh" dari dokumen HTML.
- **Definisi:** Elemen `<body>` berisi semua konten yang akan terlihat oleh pengguna di halaman web, seperti teks, gambar, tabel, dan elemen-elemen lain yang dapat dirender oleh browser.
- **Fungsi:** Semua elemen yang ada di dalam `<body>` akan ditampilkan di layar pengguna ketika mereka mengakses halaman web.

### 4. **Tag `<table>`**

- **Singkatan:** "Table" adalah kata bahasa Inggris yang berarti "tabel".
    
- **Definisi:** Elemen `<table>` digunakan untuk membuat tabel di dalam halaman web. Tabel adalah cara untuk menyusun data secara terstruktur dalam baris dan kolom.
    
- **Fungsi:** Tabel digunakan untuk menampilkan data yang terkait secara logis, seperti jadwal, daftar produk, atau data statistik.
    
- **Atribut `border="1"`:**
    
    - **Definisi:** Atribut `border` mengatur ketebalan garis border (garis tepi) di sekitar tabel dan sel-sel di dalamnya.
    - **Fungsi:** Dengan `border="1"`, tabel akan memiliki border dengan ketebalan 1 pixel, membuat garis batas di sekitar tabel dan setiap selnya.

### 5. **Tag `<thead>`**

- **Singkatan:** "Thead" adalah singkatan dari **Table Head**.
- **Definisi:** Elemen `<thead>` digunakan untuk mendefinisikan bagian kepala (header) dari tabel. Ini biasanya digunakan untuk mendefinisikan baris judul kolom.
- **Fungsi:** Baris dalam `<thead>` biasanya berisi informasi tentang kolom-kolom di tabel, seperti judul atau nama kolom, yang memudahkan pengguna untuk memahami data di bawahnya.

### 6. **Tag `<tr>`**

- **Singkatan:** "Tr" adalah singkatan dari **Table Row**.
- **Definisi:** Elemen `<tr>` digunakan untuk mendefinisikan baris dalam tabel. Setiap baris tabel dibungkus dalam satu tag `<tr>`.
- **Fungsi:** Tag `<tr>` menyusun sel-sel data (`<td>`) dalam satu baris horizontal di tabel.

### 7. **Tag `<td>`**

- **Singkatan:** "Td" adalah singkatan dari **Table Data**.
- **Definisi:** Elemen `<td>` digunakan untuk mendefinisikan sel dalam sebuah baris tabel. Setiap sel berisi data yang berada di dalam kolom tabel.
- **Fungsi:** Tag `<td>` menyusun data dalam kolom dan baris di tabel. Ini adalah elemen dasar yang mengisi tabel dengan data.

### 8. **Tag `<tbody>`**

- **Singkatan:** "Tbody" adalah singkatan dari **Table Body**.
- **Definisi:** Elemen `<tbody>` digunakan untuk membungkus konten utama dari tabel, yaitu semua baris data tabel, kecuali baris header (`<thead>`) dan baris footer (`<tfoot>`, jika ada).
- **Fungsi:** Ini adalah bagian dari tabel di mana data yang ingin ditampilkan disusun. Dalam kode yang kamu berikan, `<tbody>` membungkus satu baris data tentang permainan "harvest moon".

### **Konsep-Konsep Penting:**

1. **Struktur Tabel:**
    
    - **Tabel** dalam HTML dipecah menjadi beberapa bagian utama: **header** (yang diwakili oleh `<thead>`), **body** (yang diwakili oleh `<tbody>`), dan **footer** (yang diwakili oleh `<tfoot>` jika ada).
    - Setiap **baris** dalam tabel didefinisikan dengan tag `<tr>`.
    - Setiap **sel** dalam baris didefinisikan dengan tag `<td>` (atau `<th>` untuk header).
2. **Penggunaan Tabel untuk Menyusun Data:**
    
    - Tabel digunakan untuk menyusun data yang terkait secara logis. Misalnya, dalam tabel yang kamu buat, kamu menyusun data tentang sebuah permainan dengan kolom-kolom yang menjelaskan judul permainan, durasi bermain, kategori permainan, dan informasi tambahan.
3. **Atribut HTML:**
    
    - Atribut seperti `border="1"` pada tag `<table>` digunakan untuk menambahkan sifat tambahan pada elemen, dalam hal ini menambahkan border pada tabel.
4. **Tag Pembungkus (Wrapper Tags):**
    
    - Tag seperti `<thead>`, `<tbody>`, dan `<tfoot>` adalah tag pembungkus yang membantu mengelompokkan bagian-bagian tertentu dari tabel. Ini membantu dalam membuat tabel lebih terstruktur dan mudah dipahami, baik oleh manusia maupun oleh mesin seperti browser atau mesin pencari.
