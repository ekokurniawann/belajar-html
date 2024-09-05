## **BELAJAR HTML**

### **1. Apa itu HTML?**

HTML (HyperText Markup Language) adalah bahasa markup standar yang digunakan untuk membangun dan merancang halaman web. HTML memberikan struktur dasar pada dokumen web dan menentukan elemen-elemen yang ditampilkan di halaman. Dengan menggunakan tag HTML, Anda dapat membuat elemen seperti teks, gambar, video, tabel, dan formulir yang ditampilkan oleh browser.

### **2. Tujuan dan Fungsi HTML**

HTML memiliki beberapa tujuan dan fungsi utama yang sangat penting dalam pembuatan web:

- **Membangun Struktur Halaman Web**: HTML menyediakan kerangka dasar halaman web. Elemen-elemen HTML digunakan untuk mengorganisasi konten dalam struktur yang dapat dimengerti oleh browser dan pembaca. Ini termasuk mendefinisikan judul, paragraf, daftar, dan elemen lainnya yang membentuk layout halaman.
    
- **Memberikan Makna Semantik**: HTML membantu memberikan makna pada konten dengan menggunakan tag semantik. Misalnya, tag `<header>` menandakan bagian header dari halaman, sementara tag `<article>` digunakan untuk konten yang berdiri sendiri. Tag semantik membantu mesin pencari dan alat bantu aksesibilitas memahami struktur dan makna konten.
    
- **Menghubungkan Halaman Web**: HTML memungkinkan pembuatan hyperlink menggunakan tag `<a>`. Dengan ini, Anda bisa menghubungkan satu halaman web dengan halaman lainnya atau sumber daya eksternal, membentuk jaringan informasi yang saling terhubung.
    
- **Menampung Multimedia**: HTML memungkinkan penyertaan berbagai elemen multimedia seperti gambar, video, dan audio secara langsung di halaman web tanpa memerlukan plugin tambahan. Ini meningkatkan pengalaman pengguna dengan menyediakan konten yang lebih dinamis dan interaktif.
    

### **3. Struktur Dasar HTML**

Setiap halaman HTML mengikuti struktur dasar tertentu yang memastikan bahwa halaman ditampilkan dengan benar oleh browser. Struktur dasar ini meliputi:

- **`<!DOCTYPE html>`**: Deklarasi ini memberi tahu browser bahwa dokumen ini menggunakan HTML5. Ini penting untuk memastikan bahwa halaman dirender dengan cara yang sesuai dengan standar HTML5.
    
- **`<html>`**: Tag root yang membungkus seluruh konten halaman. Semua elemen HTML lainnya ditempatkan di dalam tag ini.
    
- **`<head>`**: Bagian ini berisi metadata dan elemen-elemen yang tidak terlihat langsung di halaman web tetapi penting untuk pengaturan dan konfigurasi halaman. Elemen-elemen dalam `<head>` termasuk:
    
    - **`<title>`**: Menentukan judul halaman yang ditampilkan di tab browser.
    - **`<meta>`**: Menyediakan metadata seperti deskripsi halaman, charset, dan pengaturan viewport.
    - **`<link>`**: Menghubungkan ke file eksternal, seperti stylesheet CSS.
    - **`<style>`**: Menyertakan CSS internal untuk styling halaman.
    - **`<script>`**: Menyertakan JavaScript atau merujuk ke file JavaScript eksternal.
- **`<body>`**: Bagian ini berisi konten yang terlihat di halaman web. Semua elemen visual, seperti teks, gambar, video, dan tabel, diletakkan di dalam tag ini.
    

### **4. Komponen Utama HTML**

#### **Tag HTML**

Tag HTML mendefinisikan berbagai elemen di halaman web. Berikut adalah beberapa kategori tag HTML dan penjelasannya:

- **Tag Blok (Block-level elements)**:
    
    - **`<div>`**: Mengelompokkan elemen lain dan sering digunakan untuk pengaturan layout dan styling.
    - **`<h1>` hingga `<h6>`**: Tag judul yang digunakan untuk berbagai tingkat heading. `<h1>` adalah judul utama, sedangkan `<h6>` adalah judul dengan tingkat yang paling rendah.
    - **`<p>`**: Digunakan untuk paragraf teks, memberikan jarak otomatis sebelum dan sesudah teks.
    - **`<section>`**: Menandai bagian atau seksi dalam halaman yang dapat memiliki heading sendiri dan digunakan untuk mengelompokkan konten terkait.
    - **`<article>`**: Digunakan untuk konten mandiri yang dapat berdiri sendiri, seperti artikel berita atau blog post.
    - **`<header>`**: Bagian atas halaman atau bagian dari halaman, sering berisi logo, navigasi, atau informasi pengantar.
    - **`<footer>`**: Bagian bawah halaman atau bagian dari halaman, sering berisi informasi hak cipta, tautan tambahan, atau informasi kontak.
- **Tag Inline (Inline-level elements)**:
    
    - **`<span>`**: Digunakan untuk membungkus teks atau elemen inline lain tanpa memulai baris baru. Sering digunakan untuk styling bagian kecil dari teks.
    - **`<a>`**: Membuat hyperlink yang bisa mengarah ke halaman lain, sumber daya eksternal, atau bagian lain dari halaman yang sama.
    - **`<img>`**: Menyisipkan gambar ke dalam halaman. Atribut `src` menentukan lokasi gambar, sementara `alt` memberikan deskripsi alternatif jika gambar tidak dapat ditampilkan.
    - **`<strong>`**: Menandai teks yang penting atau menekankan, biasanya ditampilkan dengan huruf tebal.
    - **`<em>`**: Menandai teks yang perlu ditekankan, biasanya ditampilkan dengan huruf miring.

#### **Atribut HTML**

Atribut memberikan informasi tambahan pada tag dan memodifikasi elemen sesuai kebutuhan. Beberapa atribut umum dan fungsinya adalah:

- **`href`**: Digunakan dalam tag `<a>` untuk menentukan URL tujuan dari hyperlink.
- **`src`**: Digunakan dalam tag `<img>` untuk menentukan sumber file gambar.
- **`alt`**: Memberikan deskripsi teks alternatif untuk gambar jika gambar tidak dapat ditampilkan.
- **`id`**: Memberikan identifikasi unik pada elemen, sering digunakan dalam CSS dan JavaScript untuk merujuk elemen tersebut.
- **`class`**: Mengelompokkan elemen dengan gaya atau fungsi yang sama, memungkinkan pengaturan CSS atau pengaksesan melalui JavaScript.
- **`style`**: Digunakan untuk menambahkan gaya CSS langsung pada elemen tertentu.
- **`name`**: Digunakan dalam elemen form seperti `<input>` untuk memberikan nama pada data yang dikirimkan.

### **5. Komponen Lain dalam HTML**

#### **Formulir**

Formulir memungkinkan pengguna untuk memasukkan dan mengirimkan data. Elemen-elemen kunci dalam formulir termasuk:

- **`<form>`**: Membungkus elemen-elemen form dan menentukan metode pengiriman data (`GET` atau `POST`).
- **`<input>`**: Berbagai jenis input dari pengguna, seperti teks (`type="text"`), angka (`type="number"`), checkbox (`type="checkbox"`), dan radio buttons (`type="radio"`).
- **`<textarea>`**: Area input untuk teks yang lebih panjang.
- **`<button>`**: Tombol untuk melakukan aksi seperti submit atau reset, dengan jenis tombol yang dapat ditentukan oleh atribut `type`.

#### **Multimedia**

HTML memungkinkan penyertaan berbagai jenis media dengan tag khusus:

- **`<img>`**: Menyisipkan gambar. Atribut `src` menunjuk pada file gambar, dan `alt` memberikan deskripsi gambar.
- **`<audio>`**: Menyisipkan elemen audio dengan kontrol pemutaran. Atribut `src` menunjuk pada file audio, dan `controls` menambahkan kontrol pemutaran.
- **`<video>`**: Menyisipkan elemen video dengan kontrol pemutaran. Atribut `src` menunjuk pada file video, dan `controls` menambahkan kontrol pemutaran.

#### **Tabel**

Tabel digunakan untuk menyajikan data dalam format tabular:

- **`<table>`**: Membuat tabel.
- **`<tr>`**: Membuat baris dalam tabel.
- **`<td>`**: Membuat sel dalam baris tabel.
- **`<th>`**: Membuat sel header dalam tabel. Sel header sering digunakan untuk memberi label pada kolom atau baris tabel.

#### **Daftar**

Daftar digunakan untuk menampilkan item-item dalam urutan tertentu:

- **`<ul>`**: Daftar tidak berurutan dengan bullet points.
- **`<ol>`**: Daftar berurutan dengan nomor.
- **`<li>`**: Item dalam daftar, baik dalam daftar berurutan maupun tidak berurutan.

#### **Elemen Semantik HTML5**

HTML5 memperkenalkan elemen semantik baru yang memberikan struktur dan makna yang lebih jelas pada konten:

- **`<article>`**: Artikel mandiri atau konten yang bisa berdiri sendiri, seperti artikel berita atau posting blog.
- **`<section>`**: Bagian dari halaman yang biasanya memiliki heading dan digunakan untuk mengelompokkan konten terkait.
- **`<aside>`**: Konten sampingan yang tidak langsung terkait dengan konten utama, seperti widget atau sidebar.
- **`<figure>`**: Mengelompokkan gambar atau ilustrasi dengan keterangan.
- **`<figcaption>`**: Menambahkan keterangan untuk gambar atau ilustrasi yang ada di dalam elemen `<figure>`.

### **6. Fitur dan API HTML5**

HTML5 membawa berbagai fitur dan API baru yang meningkatkan fungsionalitas web:

- **Canvas API**: Memungkinkan penggambaran grafik 2D langsung dalam HTML menggunakan elemen `<canvas>`.
- **Geolocation API**: Mengakses lokasi geografis pengguna.
- **Web Storage API**: Menyimpan data secara lokal di browser menggunakan `localStorage` dan `sessionStorage`.
- **Audio/Video API**: Memutar audio dan video secara langsung tanpa memerlukan plugin eksternal, dengan kontrol pemutaran.

