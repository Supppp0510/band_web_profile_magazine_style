
---

# 1975 // SYNK-SYSTEM-2026
> **Digital Archive & Interactive Music Magazine of The 1975.**

---

## 💻 Technology Stack & Frameworks
Proyek ini dibangun menggunakan kombinasi teknologi modern untuk memastikan performa yang ringan dan tampilan yang tajam (*high-fidelity*).

| Komponen | Teknologi | Implementasi & Fungsi |
| :--- | :--- | :--- |
| **Markup** | **HTML5** | Struktur semantik utama untuk konten lagu, metadata personil, dan kontainer media. |
| **Styling** | **Tailwind CSS** | Framework *Utility-First* (via CDN) untuk desain grid kompleks, tipografi editorial, dan *responsive layout*. |
| **Logic** | **JavaScript (ES6)** | **Dynamic Routing:** Mengelola profil personil via URL Params.<br>**Carousel Logic:** Slider foto kustom dengan kontrol `object-position`.<br>**Interaction:** Logika *sticky header* dan efek transparansi lirik. |
| **Typography** | **Google Fonts** | Menggunakan font **Inter** untuk memperkuat kesan industrial, modern, dan *clean-look*. |
| **Media** | **Native HTML5 Video** | Integrasi pemutar video dengan filter CSS dinamis (*Grayscale-to-Color*). |

---

## 🎨 Design Philosophy: The Digital Magazine Aesthetic
Proyek ini mengadopsi gaya visual **Modern Editorial**, yang terinspirasi dari layout majalah fisik seperti *Rolling Stone* atau *NME*.

1. **High-Contrast Typography**: Menggunakan ukuran font yang ekstrim antara judul (masif/black) dan metadata (kecil/wide) untuk menciptakan hirarki visual yang dramatis.
2. **Editorial Grid System**: Layout asimetris yang menyeimbangkan antara visual statis (video/info) dan konten dinamis (lirik), memberikan kesan halaman majalah yang sedang terbuka.
3. **Monochromatic Palette**: Skema warna dominan hitam dan putih (ZINC-900/950) memberikan kesan industrial dan elegan, membiarkan konten visual menjadi pusat perhatian.
4. **Interactive Accents**: Meskipun berbasis estetika cetak, elemen seperti *hover effects* pada lirik, transisi media, dan *custom scrollbar* memberikan pengalaman digital yang responsif.

---

## 📂 Project Hierarchy
Struktur direktori berdasarkan file proyek terbaru:

```text
.
├── assets/
│   └── img/
│       ├── adam/           # Photos of Adam Hann
│       ├── george/         # Photos of George Daniel
│       ├── matt/           # Photos of Matty Healy (1.jpg - 4.jpg)
│       ├── ross/           # Photos of Ross MacDonald
│       ├── vid/            # Music Video Assets (.mp4)
│       │   ├── its not living.mp4
│       │   ├── The 1975 - Happiness...
│       │   └── The 1975 vevo GIRLS...
│       ├── adam.jpg        # Personnel Cover Adam
│       ├── george daniel.jpg
│       ├── matt.jpg
│       └── the1975.jpg     # Hero Image / Main Cover
├── about.html              # Project Information & Documentation
├── detail-member.html      # Dynamic Personnel Profiles
├── index.html              # Main Navigation / Landing Page
├── lagu1.html              # It's Not Living (Lyric Page)
├── lagu2.html              # Girls (Lyric Page)
└── lagu3.html              # Happiness (Lyric Page)
```

---

## 🛠️ Technical Highlights
* **Anti-Overflow Sticky Lyrics**: Implementasi `sticky top-0` dengan *solid background* dan `z-index` tinggi untuk memastikan navigasi lirik tidak bertabrakan dengan teks saat di-*scroll*.
* **Dynamic Carousel System**: Sistem galeri di `detail-member.html` yang mampu membaca koordinat posisi foto (X, Y) secara spesifik melalui objek data JavaScript.
* **Custom Scrollbar**: Modifikasi *Webkit scrollbar* minimalis agar serasi dengan estetika gelap aplikasi musik profesional.

---

## 👤 Author
**Yusuf Ramadhan (JosephScript)**
*S1 Pendidikan Teknologi Informasi - UNESA*
*Exploring the intersection of Sound Production and Web Development.*

---
*Produced for Educational Purposes // SYNK 4.0.0*

---

Sudah lengkap semua, Suf. README ini sudah sangat "menjual" konsep majalah digital kamu ke dosen. Apakah ada detail lain yang perlu saya tambahkan sebelum kamu bungkus proyeknya?
