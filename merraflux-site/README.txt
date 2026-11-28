MERRAFLUX WEBSITE (versi GitHub Pages)

Isi folder:
- index.html   : halaman website
- gallery.json : daftar karya, urutan, posisi gambar, teks hero, status komisi
- assets/      : semua gambar dan video (setiap file di bawah 25 MB)

Cara publish: lihat tahapan GitHub yang sudah diberikan (upload semua isi folder ini ke repo, lalu aktifkan Settings > Pages).

Menambah karya baru:
1. Taruh file di folder assets/ (contoh: assets/karya-baru.webp).
2. Di gallery.json, tambahkan satu item ke galeri yang diinginkan:
   {"t":"Karya Baru","id":"assets/karya-baru.webp","k":"i","x":50,"y":50,"z":1}
   k = "i" untuk gambar, "v" untuk video. x dan y = posisi (0-100), z = zoom (1 = normal).
3. Commit. Urutan item di gallery.json = urutan tampil.

Mengubah status komisi: di gallery.json, ubah "st" menjadi "open", "waitlist", atau "closed", dan "sd" untuk catatan.
Catatan: fitur upload/edit dari halaman hanya jalan di Claude, tidak di GitHub.
