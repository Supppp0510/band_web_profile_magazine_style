# 1975 // SYNK-SYSTEM-2026
> Digital Archive & Interactive Discography of The 1975.

---

## 💻 Tech Stack & Frameworks
Proyek ini dibangun menggunakan kombinasi teknologi modern untuk memastikan performa yang ringan dan tampilan yang tajam (high-fidelity).

* **HTML5**: Sebagai struktur semantik utama untuk konten lagu, personil, dan metadata.
* **Tailwind CSS (Framework)**: Digunakan secara ekstensif melalui CDN untuk styling Utility-First. Memungkinkan desain grid yang kompleks dan responsif tanpa file CSS eksternal yang berat.
* **JavaScript (Vanilla ES6)**: 
    * **Dynamic Routing**: Mengelola data personil (Matty, Adam, Ross, George) lewat URL Params.
    * **Carousel Logic**: Mengatur slider foto dengan kontrol `object-position` kustom.
    * **Interactive Scroll**: Menangani efek transparansi lirik saat di-scroll.
* **Google Fonts**: Menggunakan font **Inter** untuk kesan tipografi industrial dan modern.

---

## 📂 Project Hierarchy
Berdasarkan struktur direktori proyek :

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
