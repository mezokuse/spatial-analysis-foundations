# Spatial Analysis Foundations: Coordinates, Distance, and Contiguity

Proyek ini mengeksplorasi tiga pilar utama dalam analisis spasial yang diimplementasikan menggunakan **KNIME Analytics Platform**. [cite_start]Materi ini mencakup teori dasar hingga perhitungan matriks pembobot yang digunakan dalam Sistem Informasi Geografis (GIS)[cite: 13, 16].

## Konsep Utama

### 1. Koordinat Spasial
[cite_start]Mengelola lokasi menggunakan dua model data utama[cite: 17, 29]:
* [cite_start]**Model Vektor**: Menggunakan koordinat untuk membentuk titik, garis, dan area[cite: 31].
* [cite_start]**Model Raster**: Menggunakan sel grid (piksel) untuk merepresentasikan fitur spasial[cite: 33].

### 2. Perhitungan Jarak
[cite_start]Implementasi berbagai metrik jarak berdasarkan skala wilayah[cite: 34]:
* [cite_start]**Euclidean**: Jarak garis lurus (planar) untuk area kecil seperti kota[cite: 36, 37].
* [cite_start]**Geodesic**: Jarak akurat yang mempertimbangkan kelengkungan bumi (great circle) untuk wilayah luas[cite: 41, 42].
* [cite_start]**Manhattan**: Aproksimasi jarak jaringan untuk pola jalan berbentuk grid[cite: 48].
* [cite_start]**Network Distance**: Jarak jalur terpendek melalui jaringan transportasi menggunakan node dan arc[cite: 53, 54].

### 3. Contiguity (Konektivitas)
[cite_start]Menentukan hubungan antar unit spasial berdasarkan batas yang dibagi bersama[cite: 141, 142]:
* [cite_start]**Rook**: Berbagi sisi[cite: 145, 148].
* [cite_start]**Bishop**: Berbagi sudut[cite: 147, 150].
* [cite_start]**Queen**: Berbagi sisi atau sudut[cite: 146, 149].

## Tools & Referensi
* [cite_start]**Tools**: KNIME Analytics Platform[cite: 16].
* **Referensi**: Wang, F., & Liu, L. (2023). [cite_start]*Computational Methods and GIS Applications in Social Science*[cite: 242].

## Kontributor (Kelompok 3)
* [cite_start]Rizky Febrian [cite: 6]
* [cite_start]Akmal Zhafif Makarim [cite: 8]
* [cite_start]Zhafir Al-Haq Taqiyyuddin [cite: 10]
* [cite_start]Najwan Nashrul Haq [cite: 12]
