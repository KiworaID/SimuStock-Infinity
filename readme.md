# 📈 SimuStock: Infinity

**The Ultimate Single-File Stock Market Simulator**

SimuStock Infinity adalah simulasi pasar saham berbasis web yang ringan, modern, dan interaktif. Dibangun hanya dalam satu file HTML tunggal, proyek ini menggabungkan simulasi harga real-time, charting interaktif, dan analisis AI sederhana untuk membantu pengguna belajar trading tanpa risiko.

![SimuStock Dashboard Preview](./public/screenshot.png)
> *Tampilan Dashboard SimuStock Infinity (Light Mode)*

## ✨ Fitur Utama

* **🚀 Real-Time Simulation:** Algoritma pergerakan harga dinamis (Random Walk) untuk pasar saham Indonesia (IDX) dan Amerika (US).
* **🤖 AI Mentor:** Analisis pasar otomatis yang memberikan sinyal *Buy, Sell, Hold,* atau *Wait* berdasarkan teknikal sederhana.
* **📊 Interactive Charts:** Grafik harga interaktif menggunakan **Chart.js** dengan fitur *drawing tools* sederhana.
* **💼 Portfolio Management:** Sistem manajemen aset lengkap dengan perhitungan *Avg Price*, *Profit/Loss*, dan *Total Asset*.
* **🌍 Multi-Market & Currency:** Mendukung saham IDX (Rupiah) dan US Stocks (USD) dengan konversi kurs otomatis.
* **🌗 Dark/Light Mode:** Tampilan responsif dengan dukungan tema gelap dan terang.
* **⚡ Single File Architecture:** Tidak perlu instalasi rumit, cukup satu file HTML.

## 🛠️ Teknologi yang Digunakan

* **HTML5 & CSS3:** Struktur dan styling dasar.
* **Tailwind CSS (CDN):** Framework CSS untuk desain modern dan responsif.
* **Chart.js (CDN):** Library visualisasi data untuk grafik saham.
* **Vanilla JavaScript:** Logika simulasi, manajemen state, dan interaksi DOM (tanpa framework JS berat).


## 🚀 Cara Menjalankan

Karena proyek ini menggunakan arsitektur *Single File*, cara menjalankannya sangat mudah:

1.  **Clone** repository ini:
    ```bash
    git clone https://github.com/KiworaID/simustock-infinity.git
    ```
2.  Buka file **`index.html`** menggunakan browser favorit kamu (Chrome, Edge, Firefox).
3.  Selesai! Simulasi siap digunakan.

## 📝 Log Perubahan (Changelog)

**Infinity Update**
* Fix: Perbaikan logika harga saham US (USD) agar tidak menyentuh angka 0.
* New: Penambahan saham *Big Tech* (Microsoft, Amazon, Google, Meta, Netflix).

## 👨‍💻 Author

Developed with ❤️ by **[KiworaID](https://github.com/KiworaID)**

---
*Disclaimer: Aplikasi ini hanya simulasi untuk tujuan edukasi dan hiburan. Uang dan saham di dalamnya bersifat fiktif.*