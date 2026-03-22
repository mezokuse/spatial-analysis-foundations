# Analisis Spasial: Koordinat, Jarak, dan Contiguity

[cite_start]Proyek ini mengeksplorasi fondasi mendasar dalam **Sistem Informasi Geografis (GIS)** dan analisis data spasial[cite: 1, 14]. [cite_start]Materi ini mencakup teori lokasi, berbagai metrik perhitungan jarak, hingga konsep konektivitas (contiguity) yang diimplementasikan menggunakan **KNIME Analytics Platform**[cite: 14, 16].

## 📌 Topik Utama

### 1. Koordinat Spasial
[cite_start]Mendefinisikan lokasi data menggunakan sistem referensi geografis[cite: 17, 18]:
* [cite_start]**Model Vektor**: Merepresentasikan fitur dunia nyata sebagai titik, garis, dan area[cite: 30, 31].
* [cite_start]**Model Raster**: Menggunakan kisi sel (piksel) untuk menyimpan informasi spasial[cite: 32, 33].
* [cite_start]**Sistem Koordinat**: Mencakup koordinat geografis (3D/Bola seperti Latitude/Longitude) dan koordinat planar (2D/Datar seperti UTM)[cite: 19, 21, 24, 25, 27].

### 2. Metrik Jarak antar Lokasi
[cite_start]Implementasi berbagai metode pengukuran jarak berdasarkan skala wilayah penelitian[cite: 34, 35]:
* [cite_start]**Euclidean Distance**: Jarak garis lurus "as the crow flies" untuk area kecil[cite: 36, 37].
* [cite_start]**Geodesic Distance**: Perhitungan jarak akurat yang mempertimbangkan kelengkungan bumi (great circle) untuk wilayah luas[cite: 41, 42].
* [cite_start]**Manhattan Distance**: Aproksimasi jarak untuk jaringan jalan dengan pola grid[cite: 46, 48].
* [cite_start]**Network Distance**: Jarak jalur terpendek melalui jaringan transportasi (node dan arc) menggunakan algoritma tertentu[cite: 52, 53, 54].

### 3. Konsep Contiguity (Konektivitas)
[cite_start]Menentukan hubungan antar unit spasial berdasarkan batas wilayah yang bersinggungan[cite: 141, 142, 143]:
* [cite_start]**Rook**: Unit yang berbagi sisi yang sama[cite: 145, 148].
* [cite_start]**Bishop**: Unit yang hanya berbagi sudut[cite: 147, 150].
* [cite_start]**Queen**: Unit yang berbagi sisi maupun sudut[cite: 146, 149].

## 🛠️ Tools & Materi
* [cite_start]**Software**: KNIME Analytics Platform untuk komputasi dan visualisasi[cite: 16].
* **Dokumen Teori**: [Lihat Presentasi Kelompok 3](./Kelompok%203_Koordinat%20Spasial%2C%20Jarak%20antar%20Lokasi%2C%20dan%20Contiguity.pdf)

## 📚 Referensi
* Wang, F., & Liu, L. (2023). *Computational Methods and GIS Applications in Social Science*. [cite_start]CRC Press[cite: 242].
* Cliff, A. D., & Ord, J. K. (1973). *Spatial Autocorrelation*. [cite_start]London: Pion[cite: 240].

---
**Kontributor (Kelompok 3):**
[cite_start]Rizky Febrian, Akmal Zhafif Makarim, Zhafir Al-Haq Taqiyyuddin, Najwan Nashrul Haq[cite: 6, 8, 10, 12].
