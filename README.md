# AfgannSwaaPicture-
# 📸 SwaaFoto Ultimate v30.0 — Cloud Edition

**SwaaFoto** adalah aplikasi berbasis web "Self-Photo Studio" premium yang dirancang untuk memberikan pengalaman studio profesional langsung dari browser perangkat mobile. Versi **v30.0** ini dilengkapi dengan integrasi cloud otomatis ke Formspree dan sistem filter real-time.

---

## ✨ Fitur Unggulan

* **7 Professional Color Grading:**
    * `Vivid`, `Vivid Cool`, `Vivid Warm` (High Saturation)
    * `Dramatic`, `Dramatic Cool`, `Dramatic Warm` (High Contrast)
    * `Dramatic Mono` (B&W Classic)
* **Baking Engine:** Filter tidak hanya terlihat di layar, tapi diproses secara permanen ke dalam file `.jpg` saat diunduh.
* **Smart Batch Downloader:** Mengunduh 5 file sekaligus secara berurutan (4 foto single + 1 foto strip panjang).
* **Cloud Sync (Formspree):** Foto strip hasil akhir akan otomatis dikirim ke endpoint [Formspree](https://formspree.io/) sebagai backup/log aktivitas.
* **Fluid Motion UI:** Animasi *staggered*, *top-down modal*, dan efek *bounce* menggunakan Bezier Curve khusus.
* **No-Zoom Tech:** Algoritma *Center-Crop* yang memastikan rasio wajah tetap proporsional 1:1 tanpa distorsi zoom.

---

## 🚀 Cara Penggunaan

1.  **Buka Aplikasi:** Jalankan file `index.html` melalui browser (direkomendasikan Chrome/Safari di Mobile).
2.  **Pilih Filter:** Klik ikon **Adjust** di pojok kanan atas untuk memilih filter dan warna frame (Putih, Hitam, Cream, Gold).
3.  **Mulai Sesi:** Klik tombol **START SESSION**. Kamu akan mengambil 4 foto dengan jeda waktu 3 detik per foto.
4.  **Simpan & Sinkron:**
    * Setelah selesai, klik **SAVE ALL 5 PHOTOS**.
    * Sistem akan mengunduh 4 foto ke galeri.
    * Sistem akan membuat 1 foto strip panjang.
    * **Otomatis:** Foto strip dikirim ke Formspree (Endpoint: `https://formspree.io/f/maqdzorq`).

---

## 🛠️ Detail Teknis

### **Teknologi yang Digunakan:**
* **HTML5 Canvas API:** Untuk penggabungan gambar (Stitch) dan pemrosesan filter pixel.
* **MediaDevices API:** Akses kamera resolusi tinggi (1280x960).
* **CSS3 Animations:** Menggunakan keyframes `@keyframes` untuk efek flash dan transisi smooth.
* **Fetch API:** Untuk pengiriman data Base64 ke server cloud.

### **Struktur Kode:**
```javascript
const Engine = {
    state:  { /* Status Kamera & Filter */ },
    media:  { /* Kontrol Musik & SFX */ },
    cam:    { /* Logika Kamera & Capture */ },
    ui:     { /* Animasi Modal & Frame */ },
    export: { /* Download & Cloud Upload */ }
};
