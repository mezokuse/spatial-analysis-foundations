# Analisis Spasial: Koordinat, Jarak, dan Contiguity

Proyek ini mengeksplorasi fondasi mendasar dalam **Sistem Informasi Geografis (GIS)** dan analisis data spasial. Materi ini mencakup teori lokasi, berbagai metrik perhitungan jarak, hingga konsep konektivitas (contiguity) yang diimplementasikan menggunakan **KNIME Analytics Platform**.

## 📌 Topik Utama

### 1. Koordinat Spasial
Mendefinisikan lokasi data menggunakan sistem referensi geografis:
* **Model Vektor**: Merepresentasikan fitur dunia nyata sebagai titik, garis, dan area.
* **Model Raster**: Menggunakan kisi sel (piksel) untuk menyimpan informasi spasial.
* **Sistem Koordinat**: Mencakup koordinat geografis (3D/Bola seperti Latitude/Longitude) dan koordinat planar (2D/Datar seperti UTM).

### 2. Metrik Jarak antar Lokasi
Implementasi berbagai metode pengukuran jarak berdasarkan skala wilayah penelitian:
* **Euclidean Distance**: Jarak garis lurus "as the crow flies" untuk area kecil.
* **Geodesic Distance**: Perhitungan jarak akurat yang mempertimbangkan kelengkungan bumi (great circle) untuk wilayah luas.
* **Manhattan Distance**: Aproksimasi jarak untuk jaringan jalan dengan pola grid.
* **Network Distance**: Jarak jalur terpendek melalui jaringan transportasi (node dan arc) menggunakan algoritma tertentu.

### 3. Konsep Contiguity (Konektivitas)
Menentukan hubungan antar unit spasial berdasarkan batas wilayah yang bersinggungan:
* **Rook**: Unit yang berbagi sisi yang sama.
* **Bishop**: Unit yang hanya berbagi sudut.
* **Queen**: Unit yang berbagi sisi maupun sudut.

---
**Kontributor (Kelompok 3):**
Rizky Febrian, Akmal Zhafif Makarim, Zhafir Al-Haq Taqiyyuddin, Najwan Nashrul Haq.
