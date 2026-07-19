# 🕯️ Life in Weeks — Memento Mori

> *"Memento mori — ingatlah bahwa kamu akan mati."*

Sebuah visualisasi sisa minggu hidupmu. Setiap kotak = 1 minggu. Dari lahir sampai target usia.

## ✨ Fitur

- **Grid mingguan** — 52 minggu per baris, setiap baris = 1 tahun hidup (berdasarkan tanggal lahir)
- **Grouping 4 minggu** — spasi tiap 4 minggu (≈ grouping bulanan)
- **Grouping 10 tahun** — spasi tiap 10 tahun (dekade)
- **Label umur** — muncul di kelipatan 5
- **Animasi cascade** — minggu yang terlewati muncul satu per satu saat halaman dimuat
- **Progress bar** — persentase hidup yang sudah dijalani vs tersisa
- **Dark theme** — tema gelap memento mori
  - Abu-abu gelap = minggu terlewati
  - Emas berdenyut = minggu ini
  - Transparan = minggu tersisa
- **Penyimpanan lokal** — data disimpan di browser (localStorage), cukup input sekali
- **Pengaturan** — tombol ⚙️ di footer untuk edit tanggal/target kapan saja
- **Responsif** — desktop, tablet, HP

## 🚀 Cara Pakai

1. Buka `index.html` di browser
2. Masukkan **tanggal lahir** dan **target usia**
3. Klik **Mulai**
4. Scroll untuk melihat seluruh grid hidupmu

> Untuk mengubah data, klik **⚙️ Pengaturan** di footer.

## 🛠️ Teknis

Single file HTML (`index.html`). Zero dependencies. Semua dalam satu file.

- **CSS**: Custom properties, flexbox, responsive breakpoints
- **JS**: DOM manipulation, requestAnimationFrame untuk animasi
- **Storage**: localStorage untuk persistensi data

## 📦 Lisensi

MIT — bebas pakai, bebas modifikasi.
