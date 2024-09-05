### Tag di dalam `<head>`:

1. **`<title>`**:
    - Digunakan untuk menentukan judul halaman yang ditampilkan di tab browser.
    - Contoh: `<title>GOPHERS</title>`.
2. **`<link>`**:
    - Tag ini digunakan untuk menautkan file eksternal ke halaman HTML, seperti file CSS. Di proyek kamu, tag ini digunakan untuk menghubungkan file `style.css` agar halaman memiliki gaya yang sesuai.
    - Contoh: `<link rel="stylesheet" href="style.css" />` menautkan file CSS ke HTML.

---

### Tag di dalam `<body>`:

1. **`<div>`**:
    
    - Tag ini adalah elemen kontainer yang digunakan untuk mengelompokkan elemen lain di dalamnya. Kamu bisa menambahkan gaya atau pengaturan layout untuk konten di dalam `<div>`.
    - Contoh: `<div class="container">` adalah pembungkus utama untuk seluruh halaman.
2. **`<ul>`** (Unordered List):
    
    - Digunakan untuk membuat daftar yang tidak berurutan (bullet points).
    - Contoh: `<ul class="ul-navbar">` digunakan untuk membuat daftar menu navigasi di halaman.
3. **`<li>`** (List Item):
    
    - Setiap item di dalam daftar (baik yang berurutan atau tidak berurutan) ditempatkan di dalam tag `<li>`.
    - Contoh: `<li class="li-navbar">HOME</li>` adalah satu item dalam daftar menu navigasi.
4. **`<a>`** (Anchor/Link):
    
    - Tag ini digunakan untuk membuat tautan ke halaman lain atau sumber daya eksternal. Atribut `href` menentukan alamat tujuan tautan.
    - Contoh: `<a href="about.html" class="a-navbar">ABOUT ME</a>` membuat tautan ke halaman "about.html".
5. **`<img>`**:
    
    - Tag ini digunakan untuk menampilkan gambar di halaman. Atribut `src` menentukan lokasi gambar, dan atribut `alt` memberikan deskripsi alternatif jika gambar tidak bisa ditampilkan.
    - Contoh: `<img src="gophers.png" class="img-content" />` menampilkan gambar "gophers.png".
6. **`<p>`** (Paragraph):
    
    - Tag ini digunakan untuk membuat paragraf teks.
    - Contoh: `<p>CODING GOLANG YU!</p>` akan menampilkan teks di dalam paragraf.
7. **`<h1>`** hingga **`<h6>`** (Heading):
    
    - Tag ini digunakan untuk membuat judul atau subjudul. `<h1>` adalah yang terbesar, sedangkan `<h6>` adalah yang terkecil.
    - Contoh: `<h1 class="h1-footer">Webiste ini dibuat oleh Gophers</h1>` adalah judul di bagian footer dengan ukuran besar.

---

### CSS (File `style.css`):

1. **`.container`**:
    
    - Kelas `.container` digunakan untuk mengatur elemen pembungkus utama dari halaman, biasanya berfungsi sebagai kontainer untuk seluruh elemen di dalam halaman.
2. **`.container-navbar`**:
    
    - Kelas `.container-navbar` digunakan untuk membuat bagian navigasi (menu) di bagian atas halaman. Di sini, latar belakangnya diberi warna biru dengan lebar 100% dan tinggi 10% dari layar.
3. **`.ul-navbar`, `.li-navbar`, `.a-navbar`**:
    
    - `.ul-navbar`: Mengatur daftar menu agar terlihat rapi dan sejajar secara horizontal (dengan `flex`).
    - `.li-navbar`: Setiap item daftar diberikan jarak dan padding, serta berubah warna saat di-hover.
    - `.a-navbar`: Tautan di dalam daftar diberikan warna dan dekorasi (misalnya teks tebal dan warna putih).
4. **`.container-content`**:
    
    - Kelas ini digunakan untuk mengatur tata letak bagian konten halaman. Dengan pengaturan `flex`, konten diatur agar berada di tengah halaman dengan gambar dan teks terpusat.
5. **`.a-content`, `.img-content`**:
    
    - `.a-content`: Mengatur gaya untuk tautan di dalam konten, seperti ukuran, warna, dan bayangan. Juga memberikan efek seperti kotak dengan sudut membulat dan bayangan.
    - `.img-content`: Mengatur ukuran gambar di dalam konten agar terlihat proporsional.
6. **`.container-footer`, `.h1-footer`**:
    
    - `.container-footer`: Mengatur bagian footer di halaman, yang ditampilkan di bagian bawah dengan latar belakang biru dan teks putih.
    - `.h1-footer`: Mengatur teks dalam footer agar berukuran besar dan berwarna putih.

