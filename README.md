# Web profil (Hugo + tema Toha)

## Pasang
1. Ekstrak zip, buat repo publik di GitHub (misal `username.github.io`), upload semua isinya (termasuk folder `.github`).
2. Upload CV ke `static/files/cv.pdf`.
3. Settings -> Pages -> Source: GitHub Actions. Tunggu 2-3 menit (tab Actions).
4. Ganti `baseURL` di hugo.yaml dengan alamat situsmu.

## Edit
- Nama, foto, kontak, teks animasi: data/id/author.yaml
- Tentang + tombol Unduh CV + sosmed: data/id/sections/about.yaml
- Pengalaman: data/id/sections/experiences.yaml
- Pendidikan: education.yaml, Keahlian: skills.yaml
- Artikel baru: folder baru di content/posts/<judul>/index.md (lihat contoh)
- Foto profil: assets/images/author/profile.png
- Hapus bagian yang tidak diperlukan: ubah `enable: true` menjadi `false` di file section-nya.
