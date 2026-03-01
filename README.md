# 📸 SwaaFoto V2 — The Professional Studio Experience

**SwaaFoto V2** adalah evolusi dari *Self-Photo Studio* digital yang dirancang untuk perangkat mobile. Dibangun dengan fokus pada estetika minimalis, performa tinggi, dan kualitas visual setara kamera studio profesional.

---

## 💎 Fitur Unggulan (Pro-Grade)

### 🎨 **7 Professional Color Grading**
Sistem filter yang dikalibrasi secara khusus untuk meniru karakteristik film analog dan grading sinematik:
* **Vivid Series:** `Vivid`, `Vivid Cool`, `Vivid Warm` — Warna pop, kontras tajam, kulit cerah.
* **Dramatic Series:** `Dramatic`, `Dramatic Cool`, `Dramatic Warm` — Moody, bayangan dalam, tekstur film vintage.
* **Dramatic Mono:** Hitam putih klasik dengan kontras tinggi ala majalah fashion.

### 🖼️ **Studio Canvas Baking Engine**
Teknologi render yang menyatukan filter langsung ke dalam pixel gambar. Apa yang kamu lihat di layar (*What You See*) adalah apa yang kamu dapatkan di galeri (*What You Get*).

### 📐 **Anti-Distortion No-Zoom Logic**
Algoritma *Smart-Crop* 1:1 yang menjaga proporsi wajah tetap ideal. Menghilangkan masalah kamera depan yang sering terlihat "terlalu dekat" atau "gepeng" pada browser HP.

### ⚡ **Turbo Batch Downloader**
Sekali klik, simpan seluruh sesi:
* **4 Foto Individual:** Kualitas HD untuk sosial media.
* **1 Signature Strip:** Gabungan 4 foto dalam format strip panjang dengan watermark eksklusif.

---

## 🕹️ Cara Menjalankan

1.  **Deploy:** Simpan file `index.html` di hosting atau buka langsung di browser.
2.  **Setup Assets:** Pastikan file pendukung (`pindah1.png` - `pindah4.png` dan `musik1.mp3`) berada dalam satu folder.
3.  **Capture:** Tekan **START SESSION**, bergaya dalam 4 kali jepretan otomatis.
4.  **Save:** Klik **SAVE ALL 5 PHOTOS** untuk mengunduh seluruh hasil ke galeri ponsel.

---

## 🛠️ Arsitektur Teknis

Aplikasi ini menggunakan pola **Modular Vanilla JS Engine** (Tanpa Library Luar):
* **Engine.cam**: Kendali penuh sensor kamera & pemrosesan filter real-time.
* **Engine.ui**: Animasi transisi menggunakan *Custom Bezier Curves* untuk pergerakan modal yang *smooth*.
* **Engine.export**: Komposisi gambar otomatis (Image Stitching) untuk pembuatan foto strip.

---

## 👨‍💻 Developer & Version
**Project:** SwaaFoto Studio Afgan  
**Version:** V2 (Professional Build)  
**Status:** Stable / Production Ready  

---
*© 2026 SwaaFoto Studio. Estetika Studio dalam Genggaman.*
