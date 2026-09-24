# Pemrograman-Web
Dokumentasi Pemograman Web Semester 3
# Laporan Praktikum 1: Dasar-Dasar HTML
## Bagian 1: Jawaban Pertanyaan Teori

### 1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?
**Jawab:** Berfungsi untuk memberi tahu browser bahwa dokumen tersebut menggunakan standar **HTML5**. Deklarasi ini memastikan browser merender halaman web dengan benar dalam mode standar (*standards mode*), bukan mode lama (*quirks mode*).

### 2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
**Jawab:**
* **Tag:** Penanda awal dan akhir suatu elemen (contoh: `<p>` dan `</p>`).
* **Elemen:** Komponen utuh yang terdiri dari tag pembuka, isi/konten, dan tag penutup (contoh: `<p>Ini paragraf</p>`).
* **Atribut:** Informasi tambahan yang disisipkan di dalam tag pembuka untuk mengatur perilaku atau tampilan elemen (contoh: `href` pada tag `<a>`).

### 3. Apa perbedaan `<p>` dengan `<br>`? Jelaskan penggunaannya.
**Jawab:**
* **`<p>` (Paragraph):** Digunakan untuk membuat paragraf baru. Secara otomatis memberikan jarak vertikal (margin/spasi) sebelum dan sesudah paragraf.
* **`<br>` (Break):** Digunakan untuk berpindah ke baris baru (*line break*) di dalam paragraf yang sama tanpa memberikan jarak vertikal ekstra.

### 4. Apa fungsi atribut `href` pada tag `<a>`?
**Jawab:** Atribut `href` (*Hypertext Reference*) berfungsi untuk **menentukan alamat tujuan** (URL atau jalur file) ke mana pengguna akan diarahkan saat mengklik teks/gambar di dalam tautan tersebut.

### 5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
**Jawab:**
* **Hyperlink Internal:** Mengarah ke halaman web lain yang berada di dalam proyek atau server yang sama (contoh: `<a href="halaman2.html">`).
* **Hyperlink Eksternal:** Mengarah ke website milik orang lain di internet dan membutuhkan alamat URL lengkap beserta protokolnya (contoh: `<a href="https://google.com">`).

### 6. Apa fungsi atribut `src` dan `alt` pada tag `<img>`?
**Jawab:**
* **`src` (Source):** Menentukan jalur (path) atau alamat sumber file gambar yang ingin ditampilkan.
* **`alt` (Alternate Text):** Menyediakan teks alternatif yang akan muncul jika gambar gagal dimuat akibat koneksi lambat atau salah path.

### 7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?
**Jawab:**
* **`<ul>` (Unordered List):** Digunakan untuk membuat daftar item acak yang tidak membutuhkan nomor urut, biasanya ditampilkan dalam bentuk poin bulat (*bullet*).
* **`<ol>` (Ordered List):** Digunakan untuk membuat daftar item yang berurutan atau kronologis, ditampilkan dalam bentuk penomoran (1, 2, 3 atau A, B, C).

### 8. Apa yang terjadi jika path gambar pada atribut `src` salah?
**Jawab:** Gambar tidak akan muncul di halaman web. Browser hanya akan menampilkan **ikon gambar rusak** beserta **teks alternatif** yang ditulis pada atribut `alt`.

### 9. Mengapa struktur heading `h1` sampai `h6` perlu digunakan secara terstruktur?
**Jawab:** Agar struktur informasi dan hierarki konten pada halaman web menjadi logis. Struktur yang rapi mempermudah pembaca memahami isi web, serta sangat penting untuk **SEO (Search Engine Optimization)** agar mesin pencari seperti Google mudah membaca situs kita.

### 10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?
**Jawab:** Digunakan untuk memberikan catatan penjelasan atau dokumentasi di dalam kode bagi developer. Kode yang berada di dalam tanda komentar **tidak akan dieksekusi atau ditampilkan** oleh browser di halaman web.

---

## Bagian 2: Langkah Praktikum & Dokumentasi

1. Membuat Paragraf

    Penjelasan: Langkah ini bertujuan untuk mempelajari cara membuat dan menampilkan paragraf pada halaman HTML menggunakan tag p. Tag p secara otomatis memberikan jarak antar-paragraf pada tampilan browser.   

    Screenshot:
   <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-04-03" src="https://github.com/user-attachments/assets/43bc02a8-b99d-4e6d-b42a-b1e47fa1a1c4" />


2. Menambahkan Judul

    Penjelasan: Pada langkah ini, digunakan tag heading (h1 sampai h6) untuk membuat judul dan subjudul pada halaman web. h1 digunakan sebagai judul utama, sedangkan h2 digunakan untuk subjudul.   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-07-35" src="https://github.com/user-attachments/assets/235d49e3-cd99-45d7-899e-01631af10cb7" />


3. Memformat Teks

    Penjelasan: Langkah ini mencakup pengujian berbagai tag pemformatan teks, seperti (b) atau (strong) untuk cetak tebal, (i) atau (em) untuk cetak miring, (mark) untuk penanda (highlight), (sub) untuk subscript (misal: H₂O), dan (sup) untuk superscript (misal: x²).   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-11-15" src="https://github.com/user-attachments/assets/1d0be56b-8914-4373-ada7-445c4fa53eb0" />


4. Menyisipkan Gambar

    Penjelasan: Langkah ini melakukan penyisipan gambar ke halaman web menggunakan tag img dengan atribut src untuk menentukan jalur file gambar dan atribut alt sebagai deskripsi pengganti gambar.   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-29-46" src="https://github.com/user-attachments/assets/1ea76f38-9021-4540-9b4c-f8fb8572b288" />


5. Mengatur Ukuran Gambar

    Penjelasan: Mengatur dimensi dan proporsi gambar pada halaman web dengan menerapkan atribut width (lebar) dan height (tinggi) pada tag img.   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-32-46" src="https://github.com/user-attachments/assets/bcc43bc9-8b80-4c04-9b91-848fb0afa56e" />


6. Menambahkan Hyperlink

    Penjelasan: Membuat navigasi halaman menggunakan tag a dengan atribut href. Pengujian dilakukan untuk hyperlink internal (menghubungkan index.html dengan halaman2.html) dan hyperlink eksternal (mengarah ke situs luar seperti Google).   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-24 11-32-57" src="https://github.com/user-attachments/assets/ec2fa25b-5df4-40a1-80c0-44a0a449dd54" />


7. Menambahkan List

    Penjelasan: Menampilkan daftar informasi dalam bentuk poin-poin menggunakan unordered list (ul) untuk daftar tak berurutan, serta ordered list (ol) untuk daftar berurutan berangka.   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-39-02" src="https://github.com/user-attachments/assets/0215f725-24c6-4b7b-97e2-c23446bf3c04" />


8. Menambahkan Komentar

    Penjelasan: Menyisipkan baris komentar pada kode HTML menggunakan sintaks <!-- komentar -->. Komentar berfungsi untuk penanda struktur kode dan diabaikan/tidak ditampilkan oleh browser.   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-40-43" src="https://github.com/user-attachments/assets/e180d2f4-543e-4ea6-97d5-952d6191946b" />


9. Menggabungkan Semua Elemen

    Penjelasan: Tahap akhir di mana seluruh elemen yang telah dipelajari (navigasi link, heading, gambar, paragraf data diri, list keahlian, dan list target belajar) digabungkan menjadi satu halaman utuh berupa Profil Mahasiswa.   

    Screenshot:
    <img width="1366" height="738" alt="Screenshot from 2026-09-23 20-42-55" src="https://github.com/user-attachments/assets/437eb31b-d9e3-4413-97fa-2f05b6717787" />
