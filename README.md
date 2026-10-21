# Pixel Brand & Thumbnail Studio

**Coba langsung:** https://abizahyrz.github.io/pixel-brand-studio/

Pembuat thumbnail gratis yang jalan sepenuhnya di browser. Tanpa login, tanpa server, tanpa AI generatif: kamu yang mengatur teks, warna, dan karakter, jadi hasilnya konsisten dengan brand-mu.

*A free, browser-only thumbnail maker. No login, no server, no generative AI. You control the text, colors, and character, so your thumbnails stay on-brand.*

## Fitur

- Teks pixel dengan tiga gaya: **chunky** (outline + shading), **slim**, dan **retro shadow**
- Banyak teks, masing-masing dengan ukuran, gaya, warna, dan posisi sendiri
- Kanvas fleksibel: 16:9, 9:16, 1:1, 4:5, 3:1, atau ukuran kustom
- Layer teks dan gambar: pilih, geser, urutkan, sembunyikan, duplikat, plus alat pilih di kanvas
- Upload gambar (gambar besar diperkecil lewat slider Resolusi) dan karakter contoh bawaan
- Palet warna otomatis dari karakter
- Pengecek kontras (rumus WCAG) dan preview ukuran feed
- Import font sendiri (`.ttf`, `.otf`, `.woff`, `.woff2`)
- Ekspor PNG 1280×720 atau 1920×1080
- Bantuan romaji untuk teks katakana/hiragana (tidak ikut tergambar di thumbnail)

## Cara pakai

Buka `index.html` di browser. Tidak perlu instal apa pun.

## Deploy ke GitHub Pages

1. Buat repo baru, lalu unggah `index.html`, `README.md`, dan `LICENSE`.
2. Buka **Settings → Pages**.
3. Di **Source**, pilih branch `main` dan folder `/ (root)`, lalu simpan.
4. Tunggu beberapa menit. Alamatnya akan berbentuk `https://<username>.github.io/<nama-repo>/`.

## Kustomisasi

- **Link Ko-fi:** ubah `href` pada tombol dengan `id="kofi"` di `index.html`.
- **Warna brand:** ubah `const BRAND = [...]` di bagian script.

## Privasi

- Tidak ada login, analitik, atau pelacakan.
- Gambar, teks, dan font diproses di browser dan tidak diunggah ke mana pun.
- Satu-satunya permintaan keluar: memuat font dari Google Fonts. Kalau ingin nol permintaan eksternal, unduh font Pixelify Sans dan DotGothic16, lalu tanam dengan `@font-face`.
- Font yang kamu import adalah tanggung jawabmu, pastikan lisensinya mengizinkan penggunaan itu.

## Lisensi

Kode: [MIT](LICENSE). Font bawaan, Pixelify Sans dan DotGothic16, berlisensi SIL Open Font License lewat Google Fonts.
