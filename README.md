# 🌐 DUNIA TKJ

**Tugas KKA (Koding Kecerdasan Artifisial) – Modul 4: Multi Media**
Kelas X TKJ 2 • By Kelompok 4
Teknik Komputer Jaringan, SMKN 2 Banjar

Website statis berisi kumpulan materi dan video pembelajaran seputar Teknik Komputer dan Jaringan:
Komputer Jaringan, Profesi TKJ, Cloud Computing, Internet of Things, dan Smart School.
Dilengkapi halaman **Ringkasan Materi**.

## 📁 Isi Folder

| File | Fungsi |
|------|--------|
| `index.html` | Halaman utama website (HTML, CSS, dan JS jadi satu file) |
| `vercel.json` | Konfigurasi agar Vercel menayangkan sebagai situs statis tanpa build |
| `.nojekyll` | Agar GitHub Pages tidak memproses file lewat Jekyll |
| `.gitignore` | Daftar file yang tidak ikut di-upload ke Git |

## 💻 Menjalankan di Komputer
Cukup klik dua kali `index.html`. Tidak perlu instalasi apa pun.
(Butuh internet untuk memuat font Google Fonts.)

## 🚀 Deploy ke GitHub Pages
1. Buat repository baru di GitHub (misalnya `dunia-tkj`).
2. Upload **semua file** di folder ini (pastikan `index.html` ada di paling luar, bukan di dalam folder lain).
3. Buka **Settings → Pages**.
4. Pada **Source**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit. Situs tayang di `https://USERNAME.github.io/dunia-tkj/`.

## ▲ Deploy ke Vercel
**Lewat GitHub (disarankan):**
1. Upload project ke GitHub seperti langkah di atas.
2. Buka [vercel.com](https://vercel.com) → **Add New… → Project** → import repository.
3. Biarkan pengaturan bawaan (Framework Preset: **Other**, tanpa Build Command). Klik **Deploy**.

**Lewat upload langsung:**
1. Install Vercel CLI: `npm i -g vercel`
2. Jalankan `vercel` di dalam folder ini, lalu `vercel --prod`.

## ❗ Jika Terjadi Error
- **404 NOT_FOUND:** pastikan `index.html` berada di root repository, bukan di dalam subfolder.
- **Halaman kosong di GitHub Pages:** cek Settings → Pages sudah memilih branch `main` dan folder `/ (root)`.
- **Font tidak muncul:** periksa koneksi internet.
- **Perubahan tidak terlihat:** tekan `Ctrl + F5` untuk memuat ulang tanpa cache.

## 👥 Pembuat
Kelompok 4 – Kelas X TKJ 2, SMKN 2 Banjar.
