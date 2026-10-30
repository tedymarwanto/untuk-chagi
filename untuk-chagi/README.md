# Untuk Chagi

Website kecil berisi foto, lagu, surat, dan perjalanan kita.

## Isi folder

```
index.html                     ← halaman utama (semua tampilan & kode ada di sini)
assets/foto/sampul.jpg         ← foto halaman depan
assets/foto/gallery/           ← 16 foto gallery (foto-01.jpg … foto-16.jpg)
assets/foto/perjalanan/        ← 3 foto menu Perjalanan
assets/lagu/lagu-kita.m4a      ← lagu
```

## Cara online-kan pakai GitHub Pages

1. Buka github.com → **New repository** → nama: `untuk-chagi` → pilih **Public** → **Create repository**.
2. Di halaman repo, klik **uploading an existing file**, lalu drag **semua isi** folder ini
   (`index.html`, `README.md`, dan folder `assets`). Pastikan `index.html` ada di paling luar, bukan di dalam folder lain.
3. Klik **Commit changes**.
4. Buka **Settings → Pages**. Di bagian *Build and deployment*, pilih **Deploy from a branch**,
   branch **main**, folder **/(root)**, lalu **Save**.
5. Tunggu 1–2 menit. Web-nya bisa dibuka di:
   `https://USERNAME-GITHUB-KAMU.github.io/untuk-chagi/`

## Mau ganti sesuatu?

- **Foto gallery:** ganti file di `assets/foto/gallery/` dengan nama yang sama. Kalau jumlahnya berubah,
  ubah daftar ukuran foto di bagian `var FOTO = [...]` di `index.html`.
- **Lagu:** ganti `assets/lagu/lagu-kita.m4a`, lalu ubah judul/penyanyi di `index.html` (cari "James Dean").
- **Surat:** cari `<article class="surat">` di `index.html`.

Catatan: nama file di GitHub Pages peka huruf besar-kecil (`Foto-01.JPG` ≠ `foto-01.jpg`).
