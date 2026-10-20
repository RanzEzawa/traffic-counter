# Traffic Counter (open source, MIT)

Aplikasi hitung lalu lintas dua arah. Jenis kendaraan: motor, truk, **bus kecil**, bus, mobil.

## Cara pakai
- **Tap** tile = +1. **Tahan 0,6 detik** = -1 (koreksi salah tap).
- Mobil dikali **car factor** (tombol panah tengah).
- **Save and Next**: simpan interval ke log, hitungan kembali 0.
- **Reset**: nolkan hitungan interval berjalan.
- **X**: menu unduh CSV, layar penuh, hapus data.
- Data tersimpan otomatis di perangkat (tidak hilang bila halaman ditutup).

## Pasang di HP
1. Buka `index.html` langsung, atau host di GitHub Pages/Netlify (gratis).
2. Chrome Android: menu ⋮ → *Install app / Add to Home screen*. Berjalan offline.

## Struktur
`index.html` (seluruh app), `manifest.webmanifest`, `sw.js` (offline), `icon.svg`.

## Versi APK (Android)
Tiap push ke `main`, GitHub Actions membangun APK otomatis (tab **Actions** → run terbaru → *Artifacts* → `traffic-counter-apk`).
Di APK, **Save and Next** juga menyimpan gambar rekap ke galeri (Pictures/TrafficCounter). Butuh Android 10+.
