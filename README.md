# COSTOM ID – Premium Apparel & Custom Customization Landing Page

COSTOM ID adalah platform profil bisnis (landing page) dan katalog interaktif konveksi sablon premium yang melayani pemesanan pakaian kustom (T-Shirt, Polo, Jaket, Topi, Lanyard) secara satuan maupun grosir.

> 🚀 **Konteks Portofolio**: Saya mengambil alih kode sumber (*codebase*) proyek murni statis ini dari pengembang sebelumnya untuk melakukan pembersihan kode (*code cleanup*), optimalisasi komponen DOM, serta meningkatkan performa kecepatan muat halaman (*page load speed*).

---

## 🛠️ Tech Stack yang Digunakan

Proyek ini dibangun murni menggunakan teknologi web dasar (*Vanilla Web Stack*) untuk memastikan performa yang sangat ringan dan aksesibilitas tinggi:

* **HTML5**: Menyusun kerangka halaman yang semantik dan ramah SEO (Search Engine Optimization).
* **CSS3**: Mengatur tata letak (*layouting*) responsif, transisi visual, efek akordion, serta animasi slider mitra kerja.
* **Vanilla JavaScript (ES6+)**: Menangani interaktivitas halaman seperti navigasi responsif (*hamburger menu*), alur buka-tutup FAQ, dan enkapsulasi tautan pesan.

---

## ⚙️ Ringkasan Pembaruan & Refaktorisasi Saya

Sebagai developer yang merombak proyek ini, berikut adalah poin-poin optimasi teknis yang berhasil saya terapkan langsung pada file-file kode inti:

### 1. Moduliasasi Komponen Tampilan (UI & Semantic Clean Up)
* **Struktur HTML Semantik**: Memperbaiki tag-tag HTML yang berantakan menjadi lebih terstruktur (menggunakan `<header>`, `<section>`, `<main>`, `<footer>`) agar kode lebih mudah dibaca oleh developer lain (*maintainable*).
* **Komponen FAQ Interaktif**: Memperbaiki logika JavaScript pada komponen tanya-jawab (FAQ Accordion) agar transisinya berjalan mulus saat diklik tanpa merusak susunan tata letak halaman.

### 2. Pengelolaan Aset Gambar & Performa Halaman
* **Lazy Loading Galeri Karya & Koleksi**: Menerapkan atribut pemuatan tertunda (`loading="lazy"`) pada bagian *Koleksi Polosan* dan *Galeri Karya* guna mempercepat pemuatan halaman awal (*First Contentful Paint*).
* **Optimasi Animasi Slider**: Merapikan animasi CSS pada bagian teks bergerak (*scrolling marquee* logo mitra bisnis seperti Nike, Adidas, Google, dll.) agar berjalan lancar tanpa mengalami penurunan *frame rate* (patah-patah).

### 3. Integrasi Alur Pesanan (Conversion Rate Fix)
* **Validasi Tautan WhatsApp**: Mengamankan tautan parameter teks otomatis pada tombol aksi "Pesan Sekarang" dan "Chat WhatsApp Sekarang" untuk memastikan alur konsultasi pelanggan terarah langsung ke nomor admin dengan format pesan yang rapi.

---

## 📂 Struktur Repositori

```text
├── css/
│   └── style.css       # File style utama yang telah dibersihkan dari kode redundan
├── js/
│   └── main.js         # Logika interaktif FAQ, scroll anchor, dan integrasi WhatsApp
├── assets/
│   ├── img/            # Aset gambar katalog dan koleksi polosan yang sudah dikompresi
│   └── icons/          # Ikon fitur premium (garansi kualitas, free desain)
├── index.html          # Landing page utama (Semantic HTML5)
└── README.md
```

---

## 📦 Cara Menjalankan Proyek Secara Lokal

Situs web ini sepenuhnya berjalan di sisi klien (*client-side*), sehingga tidak memerlukan instalasi backend maupun server database.

1. Clone repositori ini ke komputer lokal Anda:
   ```bash
   git clone https://github.com
   ```
2. Buka folder proyek:
   ```bash
   cd costom-id
   ```
3. Klik dua kali pada file `index.html` untuk langsung membukanya di browser pilihan Anda (Google Chrome, Edge, Safari, dll.).

---

## 📝 Atribusi Bisnis
* **Hak Cipta Bisnis**: © 2026 COSTOM ID. Semua hak cipta dilindungi.
* **Refactored & Maintained by**: [@Techriz-NVM](https://github.com)
* https://techriz-nvm.github.io/costom-id-apparel/

* <img width="959" height="478" alt="image" src="https://github.com/user-attachments/assets/1ad6b990-fdb2-467b-84a3-a387fa969955" />

<img width="298" height="405" alt="image" src="https://github.com/user-attachments/assets/a26f60a5-bc9a-4e44-83a0-deb26f79c939" />
