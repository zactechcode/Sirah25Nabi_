# Product Requirement Document (PRD)
## Website Sejarah 25 Nabi (Sirah25) — Versi Pemula

---

## 1. Document Overview
* **Nama Produk:** Sirah25 Nabi
* **Status Dokumen:** Final / Diperbarui (Versi 2.1)
* **Tanggal:** 16 Oktober 2026
* **Target Teknologi:** Vanilla HTML5, CSS3, dan JavaScript (Tanpa Framework / Pemula-Friendly)

---

## 2. Latar Belakang & Tujuan Produk
* **Latar Belakang:** Banyak platform digital menyediakan sejarah nabi dalam bentuk teks panjang yang monoton. Proyek ini dibangun khusus menggunakan teknologi dasar web (*Vanilla HTML, CSS, & JS*) agar ramah dipelajari, mudah dimodifikasi oleh pemula, serta ringan diakses.
* **Tujuan Produk:** Menyajikan platform edukasi sejarah interaktif kisah 25 Nabi yang dilengkapi fitur *Book Slide* 3D bernuansa klasik tanpa ketergantungan pada *library* eksternal yang berat.

---

## 3. Spesifikasi Teknologi (Tech Stack)
* **HTML5:** Struktur semantik dokumen yang rapi dan terorganisir.
* **CSS3:** Styling murni menggunakan *Flexbox*, *Grid*, variabel warna kustom, serta efek transisi 3D (`transform: rotateY`, `perspective`) untuk animasi buku.
* **Vanilla JavaScript (ES6+):** Logika interaktif untuk pengoperasian *Book Slide*, penampil data, serta fitur waktu *realtime*.
* **Manajemen Data:** Array objek lokal (atau file `data.js` terpisah) untuk menampung data kisah 25 nabi.

---

## 4. Rincian Kebutuhan Fitur (Feature Requirements)

| ID | Modul / Fitur | Deskripsi Detail | Prioritas |
| :--- | :--- | :--- | :--- |
| **FR-01** | **Header & Waktu Realtime** | Menampilkan hari, tanggal Masehi/Hijriah, dan jam secara dinamis menggunakan fungsi `setInterval` di JavaScript. | P0 (Must-Have) |
| **FR-02** | **Katalog & Direktori 25 Nabi** | Daftar kartu (*cards*) atau daftar navigasi cepat untuk memilih urutan nabi. | P0 (Must-Have) |
| **FR-03** | **Book Slide 3D (Buku Digital)** | Komponen buku terbuka dua halaman (kiri dan kanan) berdampingan dengan nuansa kertas klasik, dilengkapi efek animasi putar 3D (*page flip*) saat berganti halaman. | P0 (Must-Have) |
| **FR-04** | **Interactive Timeline** | Garis waktu kronologis sederhana menggunakan struktur CSS murni untuk melihat rentang masa hidup para nabi. | P1 (Should-Have) |
| **FR-05** | **Pohon Silsilah Sederhana** | Bagan silsilah keluarga antar nabi berbasis struktur CSS Tree sederhana. | P2 (Nice-to-Have) |

---

## 5. Kebutuhan Non-Fungsional (NFR)
* **Clean Code & Edukatif:** Kode program dilengkapi komentar penjelas di setiap modul agar mudah dipelajari oleh pemula.
* **Performa Tinggi:** Waktu muat halaman sangat cepat (*< 1 detik*) karena tidak memuat pustaka pihak ketiga yang berat.
* **Responsif (Mobile-Friendly):** Tampilan otomatis menyesuaikan layar (bergeser menjadi satu kolom ke bawah pada perangkat *smartphone*).

---

## 6. Struktur Folder Proyek
```text
/sirah-25-nabi
│
├── index.html          # Halaman Utama (Beranda, Jam Realtime, & Book Slide 3D)
└── /assets
    ├── /css
    │   └── style.css   # Styling utama & efek transisi 3D buku
    ├── /js
    │   ├── app.js      # Logika navigasi buku & waktu realtime
    │   └── data.js     # Array data objek 25 nabi
    └── /images         # Aset pendukung (opsional)
```

---

## 7. Rencana Tahapan Pengembangan (Roadmap)
1. **Tahap 1:** Penyusunan kerangka HTML dan desain tata letak buku klasik dua halaman menggunakan CSS Grid/Flexbox.
2. **Tahap 2:** Implementasi efek animasi 3D putar halaman (*page flip*) dengan transisi CSS dan JavaScript.
3. **Tahap 3:** Pengisian data objek nabi ke dalam array dan integrasi fungsi jam waktu *realtime*.
4. **Tahap 4:** Uji coba responsivitas di berbagai ukuran layar dan perapihan dokumentasi kode.