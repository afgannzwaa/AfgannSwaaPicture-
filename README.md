#DEV- AFGAN P.N


# 📸 SwaaFoto Ultimate v31.0 — Pure Studio Edition

**SwaaFoto** adalah aplikasi *Self-Photo Studio* berbasis web yang dirancang untuk memberikan pengalaman fotografi profesional tingkat tinggi langsung dari perangkat mobile. Versi **v31.0** ini membuang semua ketergantungan eksternal untuk fokus pada **kecepatan, privasi, dan kualitas visual maksimal**.

---

## 🔥 Fitur Unggulan (Pro Studio)

* **7 Elite Color Grading:**
    * `Vivid Series`: (Normal, Cool, Warm) - Warna cerah, kontras tinggi, kulit tetap natural.
    * `Dramatic Series`: (Classic, Cool, Warm) - Moody, bayangan dalam, tekstur film yang kuat.
    * `Dramatic Mono`: Black & White dengan kontras tinggi ala majalah fashion.
* **Pro-Canvas Baking Engine:** Setiap filter yang kamu pilih di layar akan diproses secara matematis ke dalam Canvas HTML5 saat pengambilan gambar. Hasil unduhan adalah file `.jpg` berkualitas tinggi yang sudah memiliki filter permanen.
* **No-Zoom Logic (1:1 Ratio):** Menghilangkan masalah wajah yang terlihat terlalu dekat (zoomed-in). Algoritma kami mengambil sensor kamera 4:3 dan melakukan *smart-crop* ke 1:1 di titik tengah secara otomatis.
* **Infinite Animation Loop:** Setelah sesi selesai, hasil foto akan ditampilkan dalam *Polaroid Preview* dengan animasi *Slide* dan *Sticker* yang terus berganti secara dinamis.
* **Turbo Batch Downloader:** Fitur unduhan sekuensial yang mengunduh 5 file (4 Foto Individual + 1 Strip Panjang) dalam satu klik tanpa membebani RAM ponsel.

---

## 🎨 Panduan Filter

1. **Vivid Cool:** Cocok untuk outdoor atau ruangan dengan lampu putih (memberikan kesan *clean*).
2. **Dramatic Warm:** Memberikan kesan *vintage* dan *cozy*, sangat bagus untuk warna kulit sawo matang.
3. **Dramatic Mono:** Pilihan terbaik untuk foto yang ingin terlihat abadi dan elegan.

---

## 🚀 Cara Menjalankan

1. Simpan kode sebagai `index.html`.
2. Pastikan file asset seperti `pindah1.png` hingga `pindah4.png` (sticker) dan `musik1.mp3` berada dalam satu folder.
3. Buka melalui browser (Chrome/Safari recommended).
4. Tekan **START SESSION** dan bergayalah!

---

## 🛠️ Arsitektur Kode (Pure JS)

Aplikasi ini dibangun menggunakan pola **Modular Engine** tanpa *library* luar (Vanilla JS) agar sangat ringan:
- **Engine.cam**: Mengelola *stream* kamera dan filter real-time.
- **Engine.ui**: Mengelola transisi modal dan animasi Polaroid.
- **Engine.export**: Mengelola perakitan foto strip dan proses unduhan otomatis.

---

## 👨‍💻 Developer
**Project:** SwaaFoto Studio Afgan  
**Version:** 31.0 (Pure Performance Build)  
**Status:** Ready for Production  

---
*© 2024 SwaaFoto Studio. Fokus pada Kualitas, Bukan Koneksi.*
