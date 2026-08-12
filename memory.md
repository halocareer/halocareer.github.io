# Halo Career — Project Memory

## Identitas Proyek

- **Nama Project**: Halo Career
- **URL Target**: https://halo-career.github.io
- **Lokasi File**: `C:\Users\MSI\OneDrive\Documents\Claude-Work\halo-career.github.io\`
- **Relasi**: Blog companion untuk Instagram @IndoInEstonia
- **Bahasa**: Bahasa Indonesia
- **Dibuat**: 2026-07-13

## Konsep

Blog personal yang mendokumentasikan perjalanan karir seorang data analyst dari Indonesia yang mendapatkan pekerjaan di Estonia. Format konten "101 hal" — hal yang sudah dilalui, sedang dilalui, dan akan dilalui. Blog ini menjadi versi panjang dari konten Instagram @IndoInEstonia.

Setiap artikel punya nomor (#001, #002, dst.) dan terhubung ke carousel Instagram-nya kalau ada.

## Visual Identity

Sama persis dengan @IndoInEstonia:
- **Primary**: `#1E50DC` (biru Estonia)
- **Accent**: `#CF1020` (merah Indonesia)
- **Text**: `#0d0d1a`
- **Background**: `#f5f7ff`
- **White**: `#ffffff`
- **Gray**: `#6b7280`
- **Font**: Plus Jakarta Sans (Google Fonts)
- **Border radius**: 16px
- **Shadow**: `0 2px 16px rgba(30,80,220,0.08)`

## Struktur File

| File | Deskripsi | Status |
|------|-----------|--------|
| `index.html` | Homepage lengkap | Skeleton |
| `style.css` | Global stylesheet | Done |
| `post-template.html` | Template blog post individual | Skeleton |
| `instagram-skeleton.html` | Referensi desain slide Instagram | Skeleton |
| `memory.md` | File ini | Done |

## Kategori Konten (8 kategori)

| # | Nama | Deskripsi |
|---|------|-----------|
| 1 | Mencari Kerja | Tips melamar sebagai data analyst ke luar negeri |
| 2 | Administrasi | Proses visa, work permit, paperwork Estonia |
| 3 | Persiapan Berangkat | Yang harus disiapkan sebelum terbang |
| 4 | Bulan Pertama | Pengalaman 30 hari pertama di Estonia |
| 5 | Adaptasi | Budaya, orang Estonia, kehidupan kantor |
| 6 | Karir Data Analyst | Pekerjaan sebagai data analyst di Estonia |
| 7 | Struggle & Solusi | Tantangan nyata dan cara mengatasinya |
| 8 | Rindu Indonesia | Hal-hal yang dirindu dari rumah |

## Rules Penulisan

- JANGAN pakai em dashes (—)
- JANGAN pakai pola "not only... but also"
- Keduanya terasa AI-generated

## Relasi IndoInEstonia ↔ Halo Career

| Platform | Format | Depth |
|----------|--------|-------|
| Instagram @IndoInEstonia | Carousel 5-6 slide | Compact, visual |
| halo-career.github.io | Blog post | Detail, cerita panjang |

Setiap topik punya dua versi. Instagram dulu (compact) atau blog dulu (detail), tergantung konten.

## Session Log

### Session 1 (2026-07-13)
- Project dibuat sebagai kelanjutan dari @IndoInEstonia
- Shift objective ke format "101 hal" career journey
- Buat skeleton: index.html, style.css, post-template.html, instagram-skeleton.html
- Folder GitHub Pages: halo-career.github.io

### Session 2 (2026-08-12)
- Publish post-002.html: "Lima Tahap Interview Data Analyst di Perusahaan Ride-Hailing Global"
- Kategori: Mencari Kerja. Nama perusahaan dan interviewer sengaja disamarkan (general knowledge, hindari konflik penyebutan nama perusahaan spesifik)
- Update index.html: card #002 jadi live, placeholder lama (Work Permit, 30 Hari Pertama) digeser jadi #003 dan #004
- Update post-001.html: link "Selanjutnya" sekarang mengarah ke post-002.html

## Next Steps

Ketika konten sudah siap:
1. Isi artikel di `post-template.html` → duplikat per artikel
2. Update `index.html` bagian "Tulisan Terbaru" dengan artikel yang sudah ada
3. Deploy ke GitHub Pages (buat repo `halo-career.github.io`)
4. Sambungkan domain kalau perlu
