# LMS Content Studio — Interactive Slide Deck

Deck interaktif untuk workshop "Interactive LMS Content Studio".

## Cara hosting di GitHub Pages

1. Buat repository baru (atau gunakan repo yang sudah ada) di GitHub.
2. Upload semua isi folder ini (termasuk folder `assets/`) ke root repository — pastikan `index.html` ada di root.
3. Buka **Settings → Pages** di repository tersebut.
4. Pada **Source**, pilih branch (`main`) dan folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit, situs akan aktif di `https://<username>.github.io/<nama-repo>/`.

## Struktur file

```
index.html          → halaman utama (deck lengkap, semua slide + JS)
assets/              → semua gambar yang dipakai di deck (foto profil, foto buku, thumbnail, dsb.)
```

Semua resource sudah dibuat lokal (tidak lagi bergantung pada claude.ai) — file ini bisa langsung dihosting di GitHub Pages, Netlify, Vercel, atau server statis apa pun tanpa perubahan tambahan.

Satu-satunya resource eksternal yang tetap dipanggil dari CDN adalah Google Fonts (Newsreader, IBM Plex Sans, IBM Plex Mono) — ini normal dan tidak perlu diunduh manual, tetap butuh koneksi internet saat dibuka.
