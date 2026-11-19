# SANGATTA — Pusat Kota hingga Pesisir Kutai Timur

Landing page informatif tentang Sangatta, ibu kota Kabupaten Kutai Timur, Kalimantan Timur. Website ini mengenalkan kawasan Bukit Pelangi, ruang terbuka kota, landmark lokal, Danau Polder Ilham Maulana, serta pesisir Sangatta yang menghadap Selat Makassar.

Proyek dibuat sebagai pemenuhan **Special Task Web Development Bayucaraka 2027**.

## Preview Konsep

SANGATTA mengusung gaya *editorial travel* yang bersih dan modern. Visual lokal menjadi fokus utama, didukung warna hijau alami, *warm ivory*, dan aksen emas agar tetap terasa elegan serta mudah dibaca.

## Fitur Halaman

- Navbar dengan navigasi ke setiap bagian halaman.
- Hero section dengan pengenalan Sangatta dan tombol ajakan.
- Section tentang Sangatta dan Bukit Pelangi.
- Destinasi pusat kota: Taman Bukit Pandang, Monumen Nomad P-815, dan Monumen Truk Raksasa.
- Section pesisir: Pantai Kenyamukan, Teluk Bayur & Aquatik, serta Danau Polder Ilham Maulana.
- Footer berisi navigasi, lokasi, hak cipta, dan kredit pembuat.
- Tampilan responsif untuk layar laptop dan ponsel.

## Penjelasan Website per Bagian

### 1. Navbar / Navigasi Utama

Navbar berada paling atas halaman dan menampilkan identitas **SANGATTA — Kutai Timur**, menu Beranda, Pusat Kota, Pesisir, dan Tentang, serta tombol **Lihat Destinasi**.

Fungsinya adalah membantu pengunjung berpindah ke informasi yang dicari tanpa harus menggulir halaman secara manual. Setiap menu memakai tautan internal seperti `#kota` atau `#pesisir`, sehingga ketika diklik browser akan mengarahkan pengunjung ke section yang sesuai. Pada layar ponsel, menu utama disederhanakan agar tampilan tetap nyaman dan tidak penuh.

### 2. Hero Section / Halaman Pembuka

Hero section adalah bagian pertama yang terlihat ketika website dibuka. Bagian ini memakai foto panorama Bukit Pelangi sebagai visual utama, label lokasi **Kutai Timur, Kalimantan Timur**, judul “Dari bukit menuju pesisir.”, deskripsi singkat, serta tombol panah ke bagian pengantar.

Fungsinya adalah membangun kesan pertama dan menjelaskan tema website secara cepat: Sangatta memiliki kawasan pusat kota di perbukitan sekaligus akses ke pesisir Selat Makassar. Foto diberi lapisan warna gelap (*overlay*) agar tulisan tetap terbaca dengan baik.

### 3. Section “Mengenal Sangatta”

Bagian ini menjelaskan Sangatta sebagai ibu kota Kabupaten Kutai Timur, pusat pemerintahan dan aktivitas ekonomi, serta kota yang memiliki hubungan dekat dengan kawasan pesisir. Pada sisi visual, terdapat foto Masjid Agung Al-Faruq sebagai salah satu landmark di kawasan Bukit Pelangi.

Fungsinya adalah memberikan konteks sebelum pengunjung melihat daftar tempat. Tombol **Jelajahi ikon kota** mengarahkan pengunjung ke bagian destinasi pusat kota.

### 4. Section Pusat Kota dan Bukit Pelangi

Section ini berisi tiga kartu destinasi:

- **Taman Bukit Pandang** sebagai ruang terbuka hijau dan titik menikmati panorama kota.
- **Monumen Nomad P-815** sebagai ikon sejarah dan penerbangan maritim.
- **Monumen Truk Raksasa** sebagai representasi jejak industri pertambangan di Kutai Timur.

Setiap kartu memuat foto, kategori, nama, dan lokasi singkat. Di bawah kartu terdapat informasi tambahan tentang Bukit Pelangi, Masjid Agung Al-Faruq, dan Danau Polder Ilham Maulana. Fungsinya adalah memperkenalkan karakter Sangatta melalui ruang publik, landmark, dan identitas industrinya.

### 5. Section Pesisir dan Rekreasi

Bagian ini menampilkan sisi timur Sangatta yang berhadapan dengan Selat Makassar. Informasi dibagi dalam tiga kartu:

- **Pantai Kenyamukan**, untuk suasana pesisir, mangrove, dan dermaga kayu.
- **Teluk Bayur & Aquatik**, untuk wisata pantai keluarga dengan pasir dan pohon kelapa.
- **Danau Polder Ilham Maulana**, sebagai ruang rekreasi air di area kota.

Fungsinya adalah menunjukkan bahwa Sangatta tidak hanya dikenal lewat pusat kota dan aktivitas industri, tetapi juga memiliki ruang rekreasi pesisir serta ruang terbuka publik.

### 6. Closing Call-to-Action

Section penutup memakai kembali visual Bukit Pelangi dan kalimat ajakan untuk mengenal Sangatta lebih dekat. Tombol **Kembali ke atas** mengarahkan pengguna ke bagian awal halaman.

Fungsinya adalah menutup alur cerita website dengan visual yang kuat dan memberi cara cepat bagi pengunjung untuk kembali ke navigasi utama.

### 7. Footer

Footer adalah bagian paling bawah yang menampilkan identitas website, deskripsi singkat, tautan navigasi, lokasi, hak cipta, serta kredit pembuat **Fadlan Iffat Inayat**.

Fungsinya adalah menjadi penutup informasi, memperjelas kepemilikan karya, dan memberi akses ulang ke bagian penting website.

## Penjelasan Desain dan Responsivitas

Website memakai kombinasi font **Bodoni Moda** untuk judul agar terasa editorial dan elegan, serta **Manrope** untuk isi teks agar tetap bersih dan mudah dibaca. Warna hijau tua dipakai sebagai identitas alam dan kota, warna *warm ivory* membuat halaman terasa hangat, sedangkan emas hanya dipakai sebagai aksen penting.

Untuk menyusun layout, **Flexbox** digunakan pada navbar dan elemen yang tersusun dalam satu arah, sedangkan **CSS Grid** digunakan pada kartu destinasi dan section dengan beberapa kolom. Pada layar kecil, media query mengubah layout beberapa kolom menjadi satu kolom, memperkecil judul, menyesuaikan tinggi foto, dan merapikan jarak agar tidak muncul *horizontal scroll*.

## Teknologi yang Digunakan

- **HTML5** — struktur halaman semantik menggunakan `header`, `nav`, `main`, `section`, `article`, dan `footer`.
- **CSS3** — styling, CSS Variables, Flexbox, CSS Grid, serta media queries.
- **Google Fonts** — Bodoni Moda dan Manrope.

> Proyek ini hanya menggunakan HTML dan CSS. Tidak menggunakan JavaScript, framework, Bootstrap, Tailwind, maupun library animasi.

## Struktur Folder

```text
Nama_NRP_Departemen_KPP-Webdev/
├── index.html          # Struktur dan konten halaman
├── style.css           # Seluruh styling dan responsivitas
├── image/              # Foto-foto pendukung destinasi Sangatta
└── README.md           # Dokumentasi proyek
```

## Cara Menjalankan

1. Unduh atau clone repository ini.
2. Pastikan folder `image/` tetap berada satu folder dengan `index.html`.
3. Buka file `index.html` menggunakan browser, misalnya Google Chrome atau Microsoft Edge.

Tidak diperlukan instalasi atau konfigurasi tambahan.

## Identitas 

| Keterangan | Detail |
| --- | --- |
| Nama | Fadlan Iffat Inayat |
| NRP | 5027261098 |
| Departemen | Teknologi Informasi|

## Ketentuan Tugas yang Dipenuhi

- [x] Tema landing page jelas: informasi destinasi Sangatta, Kutai Timur.
- [x] Memiliki navbar, hero section, bagian informasi/fitur, dan footer.
- [x] Menggunakan tag HTML semantik.
- [x] Terdapat file utama `index.html` dan `style.css`.
- [x] Hanya menggunakan HTML dan CSS.
- [x] Memakai gambar pendukung dengan teks alternatif (`alt`) yang relevan.
- [x] Navigasi dan tombol CTA mengarah ke section terkait.
- [x] Layout responsif untuk perangkat mobile.
- [x] README memuat judul proyek, deskripsi, dan nama peserta.

## Catatan

Sebelum mengumpulkan, ganti bagian **NRP** dan **Departemen** pada tabel identitas peserta. Repository sebaiknya dibuat public menggunakan format nama:

```text
Nama_NRP_Departemen_KPP-Webdev
```

---

© 2027 SANGATTA — dibuat oleh **Fadlan Iffat Inayat**.
