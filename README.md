# ⚡ Simulasi Sirkuit Listrik 3D Interaktif

Sebuah simulasi 3D berbasis web yang memvisualisasikan prinsip dasar sirkuit listrik arus searah (DC). Proyek ini dirancang untuk tujuan edukasi, membantu siswa memahami konsep arus konvensional versus aliran elektron, Hukum Ohm, dan fungsi saklar dalam sirkuit.

<img width="1366" height="607" alt="screencapture-threejs-dc-circuit-vercel-app-2025-12-26-20_54_48" src="https://github.com/user-attachments/assets/1b6a8b55-2b46-4035-bb0a-51cc8393e6a4" />

## 🌟 Fitur Utama

### Visualisasi Arus Ganda
* **Arus Konvensional:** Partikel kuning bergerak dari kutub Positif (+) ke Negatif (-).
* **Aliran Elektron:** Partikel biru bergerak dari kutub Negatif (-) ke Positif (+), merepresentasikan pergerakan fisik elektron yang sebenarnya.

### Interaktivitas Penuh
* **Saklar Mekanis:** Animasi tuas saklar yang memutus dan menyambungkan sirkuit secara visual.
* **Slider Tegangan (Voltage):** Atur tegangan baterai dari **0V hingga 12V** dan lihat dampaknya secara real-time.

### Efek Visual Realistis
* **Pencahayaan Dinamis:** Bola lampu berpijar (*glowing*) semakin terang seiring kenaikan tegangan.
* **Kecepatan Arus:** Partikel bergerak lebih cepat saat tegangan dinaikkan, mensimulasikan kenaikan arus (Hukum Ohm).
* **Post-Processing:** Menggunakan efek *Bloom* untuk memberikan nuansa sci-fi dan pendaran cahaya yang indah.

## 🚀 Cara Menjalankan

Proyek ini dibuat sebagai **Single File HTML**, yang berarti Anda tidak perlu menginstal server atau dependensi rumit.

1.  Unduh file `index.html`.
2.  Buka file tersebut menggunakan web browser modern (Google Chrome, Firefox, Edge, atau Safari).
3.  Simulasi akan langsung berjalan!

> **⚠️ Catatan Penting:** Pastikan perangkat Anda terhubung ke internet saat pertama kali membuka file, karena simulasi memuat pustaka **Three.js** melalui CDN.

## 🎮 Kontrol Pengguna

| Kontrol | Fungsi |
| :--- | :--- |
| **Saklar Utama** | Klik tombol ini untuk membuka atau menutup sirkuit. Arus hanya akan mengalir jika saklar tertutup. |
| **Mode Visualisasi** | Klik untuk mengganti tampilan antara Arus Konvensional (Kuning) dan Aliran Elektron (Biru). |
| **Slider Tegangan** | Geser untuk mengubah nilai Volt. Perhatikan perubahan pada terang lampu dan kecepatan partikel. |

### Navigasi Kamera
* **Klik Kiri & Geser:** Memutar kamera (*Orbit*).
* **Scroll Mouse:** Zoom in / Zoom out.

## 🛠️ Teknologi yang Digunakan

* **[Three.js](https://threejs.org/):** Pustaka inti untuk rendering grafis 3D.
* **HTML5 & CSS3:** Struktur antarmuka pengguna (UI overlay) dengan gaya *Glassmorphism*.
* **JavaScript (ES6+):** Logika simulasi dan animasi.
* **TWEEN.js:** Pustaka kustom ringan (terintegrasi) untuk animasi halus pada saklar.

## 📚 Konsep Edukasi

Simulasi ini dirancang untuk mendemonstrasikan konsep fisika berikut:

1.  **Hukum Ohm ($I = \frac{V}{R}$)**
    Saat tegangan ($V$) naik dan hambatan ($R$) diasumsikan tetap, arus ($I$) akan meningkat. Hal ini divisualisasikan dengan pergerakan partikel yang menjadi lebih cepat.

2.  **Sirkuit Tertutup vs Terbuka**
    Listrik hanya mengalir ketika lintasan tertutup sempurna (saklar tersambung).

3.  **Miskonsepsi Arus**
    Menjelaskan perbedaan historis antara arah arus yang disepakati secara umum (**Konvensional**) dan gerakan partikel subatomik yang sebenarnya (**Elektron**).

---

*Dibuat dengan ❤️ menggunakan Three.js*
