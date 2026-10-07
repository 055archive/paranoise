# PARANOISE — Official Band Website & Electronic Press Kit (EPK)

Website portofolio resmi untuk band **Paranoise** (Alternative Pop).

---

## 🎵 Fitur Utama
1. **Hero Section (Spotlight: GUGUR)**
   - Menyorot rilisan terbaru *GUGUR* (Single 2026).
   - Efek piringan hitam (vinyl) interaktif yang berputar saat musik diputar.
   - Tombol putar web preview, direct link Spotify, dan baca lirik lagu.
2. **The Discography (4 Single Resmi)**
   - *GUGUR* (2026)
   - *Anything For You* (2026)
   - *Memori* (2025)
   - *Berharap* (2024)
   - Dilengkapi cover art resmi dari Spotify CDN, cuplikan lirik, pop-up lirik lengkap, dan tautan langsung ke Spotify.
3. **Visual Archive (Gallery & Lightbox)**
   - Menampilkan 5 foto live performance panggung Paranoise + foto formasi band.
   - Mode Lightbox interaktif: klik foto untuk melihat dalam resolusi tinggi dan membaca cerita di balik momen tersebut.
4. **Electronic Press Kit (EPK) & Booking Hub**
   - Dikhususkan untuk Promotor Acara, Penyelenggara Festival, dan Media.
   - Tombol salin data ringkasan band untuk press release.
   - Direct Call-to-Action ke **WhatsApp Booking Manager** (`089525237683`), **Email Resmi** (`paranoisemusic696@gmail.com`), dan **Instagram** (`@prnois`).
5. **Persistent Floating Audio Player**
   - Mini player di bagian bawah layar yang tetap aktif saat pengunjung menjelajah seluruh halaman.
   - Menggunakan browser Web Audio API untuk menghasilkan harmoni dreamy/ambient alt-pop yang menenangkan.
   - Tombol kontrol play, pause, next track, prev track, volume slider, dan direct Spotify stream.

---

## 🚀 Cara Menjalankan Website

### Cara Paling Mudah (Langsung Buka di Browser):
Cukup **klik dua kali (double click)** file `index.html` di dalam folder ini menggunakan browser apa saja (Google Chrome, Microsoft Edge, Firefox, Brave). Website akan langsung berjalan secara sempurna tanpa perlu install software apapun!

### Cara Deploy ke Internet Gratis (Vercel / Netlify / GitHub Pages):
1. **Netlify Drop (Paling Cepat):**
   - Buka [app.netlify.com/drop](https://app.netlify.com/drop)
   - Tarik (drag-and-drop) folder `paranoise-website` ke halaman tersebut.
   - Dalam 10 detik, website kalian sudah aktif online dengan link publik (bisa dihubungkan ke domain khusus seperti `paranoiseofficial.com`)!
2. **Vercel / GitHub Pages:**
   - Upload file-file ini ke repository GitHub.
   - Hubungkan ke Vercel untuk deployment otomatis.

---

## 📁 Struktur Folder
```
paranoise-website/
├── index.html              # Website utama (React + Tailwind CSS)
├── README.md               # Dokumentasi panduan
└── assets/                 # Aset multimedia
    ├── logo.png            # Logo resmi Paranoise (PNG transparan)
    ├── band-hero.png       # Foto formasi band Paranoise
    ├── gugur.jpg           # Cover art single GUGUR
    ├── anything-for-you.jpg# Cover art single Anything For You
    ├── memori.jpg          # Cover art single Memori
    ├── berharap.jpg        # Cover art single Berharap
    ├── gallery-1.jpg       # Foto live gitaris (I Love My Jellia)
    ├── gallery-2.jpg       # Foto live drummer fisheye
    ├── gallery-3.jpg       # Foto penonton live singalong
    ├── gallery-4.jpg       # Foto panggung synth player
    └── gallery-5.jpg       # Foto panggung live guitars double exposure
```

---

## 🎨 Menambah Foto atau Single Baru di Masa Depan
1. **Menambah Foto Baru:** Taruh foto di dalam folder `assets/`, lalu buka `index.html` dan tambahkan 1 baris di array `GALLERY_ITEMS`.
2. **Menambah Single Baru:** Buka `index.html` dan tambahkan data single baru ke dalam array `SINGLES_DATA`.
