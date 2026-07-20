# Tugas 1 & 3 — Kartu Profil (Restyled)

Tugas praktik untuk mata pelajaran PPLG, kelas XII PPLG SMT 2.
Ini adalah versi lanjutan dari Tugas 1 ("Card Profil Sederhana"), yang
dipercantik ulang sesuai instruksi Tugas 3 ("Mini Styling Project").

## Nama
Akmal Fahreza

## Deskripsi
Kartu profil dengan layout split-screen: foto besar di satu sisi, dan
informasi diri di sisi lain (nama, deskripsi, tag, statistik singkat,
dan tombol kontak). Tema visual hitam elegan dengan aksen emas.

## Poin Styling yang Digunakan
- **Warna** — palet gelap dengan aksen emas (`--gold`, `--gold-bright`)
  dan teks krem lembut (`--ink`, `--muted`)
- **Background** — gradasi radial halus di halaman, foto dengan overlay
  gradient gelap di bagian bawah
- **Font** — kombinasi *Fraunces* (serif, untuk nama) dan *Inter*
  (sans-serif, untuk teks isi)
- **Border** — garis tipis (hairline) di sekeliling card, tag, dan
  pembatas bagian statistik
- **Border radius** — halus dan konsisten (card 10px, tombol & tag 4px,
  tidak berlebihan)
- **Hover effect** —
  - Card terangkat sedikit + border menyala emas
  - Foto membesar (zoom) dan warnanya dari grayscale jadi berwarna
  - Tombol berubah solid emas dengan jarak huruf melebar
  - Tag mendapat border emas saat disentuh

## Struktur Halaman
- Panel foto (kiri/atas) dengan label kecil
- Panel info (kanan/bawah): eyebrow label → nama → deskripsi → tag
  minat → statistik kelas & jurusan → tombol kontak

## Cara Menjalankan
1. Buka `preview.html` di browser untuk melihat tampilan lengkap
   (HTML + CSS digabung dalam satu file).
2. Atau gunakan `index.html` bersama `style.css` sebagai dua file
   terpisah (struktur produksi).
3. Coba perkecil lebar browser untuk melihat tampilan responsive
   di layar kecil.

## Struktur File
```
index.html      -> Struktur HTML (menghubungkan ke style.css)
style.css       -> Semua styling (warna, layout, hover, responsive)
preview.html    -> Versi satu file untuk pratinjau/screenshot
README-tugas1-3.md -> Dokumentasi tugas ini
```

## Teknologi yang Digunakan
- HTML5
- CSS3 (Flexbox, gradient, transition, hover effect, media query)
