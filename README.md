# Sirah25 Nabi — Platform Edukasi Sejarah Islam & Book Slide 3D
### Tahap Evaluasi: Draft Teknis Awal (Mata Kuliah Pemrograman Web)

Website edukasi sejarah 25 Nabi dan Rasul dalam Islam yang dibangun menggunakan **Vanilla HTML5, CSS3, dan Minimal JavaScript** tanpa ketergantungan library/framework berat. Menampilkan pengalaman membaca visual **Book Slide 3D bernuansa mushaf klasik**, direktori lengkap 25 nabi, garis waktu peradaban, pohon silsilah nasab, laporan ringkas teknis, serta bukti kerja sama kelompok.

---

## 🎯 Aspek Penilaian yang Dipenuhi (Draft Teknis Awal)

1. **Kelengkapan Struktur Semantik HTML5:**
   - Menggunakan landmark resmi: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<table>`, dan `<footer>`.
   - Menggunakan atribut aksesibilitas (`aria-label`, `role`, heading hierarchy berjenjang H1-H4).
   - Seluruh data 25 nabi termuat langsung dalam markup HTML terstruktur.

2. **Kualitas Styling CSS3:**
   - Penggunaan variabel kustom (`:root`) untuk mempermudah pemeliharaan palet warna manuskrip klasik (emas, zamrud, perkamen, kulit cokelat).
   - Efek 3D Book Slide (`perspective: 2500px`, `transform-style: preserve-3d`, bayangan lipatan tengah buku, ornamen sudut arabesque, dan pita pembatas).
   - Sistem tata letak modern murni CSS Grid dan Flexbox yang 100% responsif lintas perangkat (desktop, tablet, smartphone).
   - Bagan silsilah keluarga nasab murni CSS (*CSS Genealogy Tree*).

3. **Kejelasan Presentasi & Demo:**
   - Seksi khusus **Live Showcase Book Slide 3D** yang siap dipresentasikan di hadapan dosen/guru penilai.
   - Dilengkapi kontrol demo untuk memilih nabi dan membalik lembaran bab secara langsung.
   - Menu navigasi anchor yang mempermudah demonstrasi bagian-bagian halaman web.

4. **Kerja Sama Kelompok & Pembagian Peran:**
   - Seksi khusus **Tim Kami** (`#kelompok`) yang memaparkan profil 4 anggota kelompok, NIM, peran spesifik teknis, dan tabel matriks pembagian kontribusi 25% merata.
   - Dokumen formal laporan teknis awal tersedia di [`LAPORAN_DRAFT_TEKNIS_AWAL.md`](LAPORAN_DRAFT_TEKNIS_AWAL.md).

---

## 📁 Struktur Berkas Proyek

```text
/webROIS
│
├── index.html                       # Dokumen utama (HTML5 Semantik, Showcase 3D, Katalog, Timeline, Tim)
├── LAPORAN_DRAFT_TEKNIS_AWAL.md     # Dokumen laporan formal evaluasi draft teknis
├── README.md                        # Ringkasan informasi dan panduan menjalankan proyek
├── prd_website_sejarah_25_nabi.md   # Dokumen PRD acuan pengembangan
└── assets/
    ├── css/
    │   └── style.css                # Sistem styling CSS3 murni & efek 3D manuskrip klasik
    └── js/
        ├── data.js                  # Database objek 25 nabi dengan bab-bab multi-page
        └── app.js                   # Skrip ringan untuk jam realtime, demo buku, & filter katalog
```

---

## 🚀 Cara Menjalankan Website

Karena website ini dibangun secara murni tanpa dependensi eksternal (*Zero Dependencies*):

1. Buka folder proyek `d:\website\webROIS` di File Explorer.
2. Klik ganda berkas **`index.html`** untuk langsung membukanya di peramban web modern (Google Chrome, Microsoft Edge, Mozilla Firefox, dll).
3. Anda juga dapat menjalankannya dengan ekstensi **Live Server** di VS Code.
# Sirah25Nabi_
