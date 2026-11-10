# Panduan admin

## Pasang sekali
1. Timpa `index.html` situsmu dengan yang baru, tambahkan `admin.html`, folder `data/` (berisi `site.json`) dan folder `covers/`.
2. Upload ke hosting. Halaman admin ada di `https://situsmu/admin.html`.

## Rilis game baru
1. Buka `admin.html` > Game > **+ Game baru**.
2. Isi nama, platform, versi, link unduh, link YouTube, pilih foto cover.
3. Tab **Publikasi** > **Publikasikan sekarang** (butuh token GitHub, lihat di halaman itu), atau **Unduh paket ZIP**, ekstrak ke folder situs, lalu upload ulang.

## Catatan
- Admin tidak punya password sendiri. Siapa pun bisa membuka halamannya, tetapi hanya pemilik token GitHub yang bisa menyimpan perubahan. Jangan bagikan tokennya.
- Cara ZIP aman dipakai di hosting apa pun karena admin tidak menyimpan apa-apa ke server.
- Data situs ada di `data/site.json` (game, WIP, pendukung, kontak, donasi). Isi `index.html` lama jadi cadangan kalau file itu tidak terbaca.
- Draf otomatis disimpan di browser sampai dipublikasikan.
