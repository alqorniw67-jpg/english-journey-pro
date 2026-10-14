# English Journey Pro

PWA belajar bahasa Inggris 30 hari untuk pemula Indonesia. HTML, CSS, dan JavaScript murni. Tanpa server, tanpa login, tanpa API berbayar.

## File
index.html, manifest.webmanifest, sw.js, icon.svg, README.md (taruh semuanya di satu folder yang sama).

## Menerbitkan di GitHub Pages (repository baru)
1. Buka github.com, klik **New repository**. Beri nama baru, misalnya `english-journey-pro`. Pilih **Public**, lalu **Create repository**. Repository English Journey lama tidak tersentuh.
2. Klik **uploading an existing file**, tarik kelima file ke halaman itu, lalu klik **Commit changes**.
3. Buka **Settings > Pages**. Di Source pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu **Save**.
4. Tunggu 1-2 menit. Alamatnya: `https://USERNAME.github.io/english-journey-pro/`
5. Android: buka alamat itu di Chrome, tunggu sampai halaman termuat, lalu menu titik tiga > **Instal aplikasi** (atau **Tambahkan ke layar utama**). Buka aplikasi sekali saat online agar file tersimpan untuk mode offline.

## Catatan
- Data tersimpan di localStorage browser/perangkat itu saja. Gunakan **Profil > Ekspor JSON** untuk backup dan **Impor JSON** untuk memulihkan atau pindah perangkat.
- Setelah mengubah file, naikkan versi cache di `sw.js` (`ejp-v2` menjadi `ejp-v3`) agar pengguna mendapat pembaruan.
- Tombol Dengar memakai suara bawaan perangkat (speechSynthesis); kualitasnya tergantung perangkat.
- Aplikasi tidak mencantumkan nomor halaman buku. Setiap fase hanya menunjuk buku rujukan; cocokkan topik dengan daftar isi bukumu.
