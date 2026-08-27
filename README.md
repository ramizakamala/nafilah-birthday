# Happy 20th, Nafilah ♥

Website kejutan ulang tahun untuk **Nafilah Nur Imtiyaz** — clean, romantis, glassmorphism halus, dengan 20 harapan, surat cinta, galeri polaroid, dan musik piano lembut (generated via WebAudio, tanpa file audio).

Live: https://ramizakamala.github.io/nafilah-birthday/

## Cara ganti isi

**Tambah / ganti foto** — taruh foto di folder `photos/` dengan nama `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg` (harus persis, huruf kecil). Langsung kebaca otomatis, nggak perlu ubah kode. Kalau fotonya lebih dari 4, tambah file `5.jpg` dst. dan ubah array `captions` di `index.html`.

**Ubah teks surat** — cari bagian `<section id="surat">` di `index.html`, edit paragrafnya.

**Ubah 20 harapan** — cari array `wishes` di bagian `<script>`.

## Cara update & push

```
git add -A
git commit -m "update"
git push
```

Butuh ~1 menit setelah push sampai GitHub Pages rebuild.
